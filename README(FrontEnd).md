# Frontend



## πλͺ©ν

- Android Studio λ₯Ό μ΄ν΄νκ³  νμ©ν  μ μλ€.
- Kotlin, xml μ½λ©μ ν΅ν΄ μ΄νλ¦¬μΌμ΄μμ κΈ°λ₯λ€μ κ΅¬νν  μ μλ€.
- νμΌλ‘ μμνμ¬ μλμ§λ₯Ό λ΄κ³ , μλ‘μ΄ μμ΄λμ΄ λ±μ μΆκ°νμ¬ νμ΅ν κ²°κ³Όλ₯Ό κ΅¬νν  κΈ°ν λ° μ€κ³

------

β λΉν μλ²λ₯Ό κ΅¬μΆ

β μ€κ³μ

- νλ©΄ μ€κ³μ(WireFrame)
- REST API

β μμ€ μ½λ

- νλ‘μ νΈ κ΄λ ¨ μ΄νλ¦¬μΌμ΄μ νλ‘ νΈμλ μ μ²΄ μμ€
- λ μ΄μμ λμμΈ, κΈ°λ₯ λ° μ¬μ©λ λ¦¬μμ€

<hr>



## κ°λ°

- Android Studio λ μ΄μμ κ΅¬μ± λ° κΈ°λ₯ κ΅¬ν

## κ΅¬μ‘°

μλλ‘μ΄λapp νλ‘μ νΈ κ΅¬μ‘°λ ν¬κ² manifestμ java, resouce, Gradle ν¨ν€μ§λ‘ μ΄λ£¨μ΄μ Έ μλ€.


manifest :β "AndroidManifest.xml"λ λ¨ νλμ νμΌμ΄ λ΄κ²¨μ Έ μμΌλ©°, μλλ‘μ΄λμ μ»¨νΈλ‘€ νμλΌκ³  μ΄ν΄νλ©΄ λλ€. μλλ‘μ΄λ μ΄νλ¦¬μΌμ΄μμ κ΅¬λνλλ° νμν μ€μ κ°μ κ΄λ¦¬ν΄μ£Όλ κ³³μ΄λ€. 

    μ νλ¦¬μΌμ΄μ κ΅¬μ± μ λ³΄λ₯Ό λ΄κ³  μλ νμΌ. μ νλ¦¬μΌμ΄μμ κ΅¬μ±νλ μ λ°μ μΈ κΈ°λ₯μ λν λͺμΈλ₯Ό ν¬ν¨.
    μλλ‘μ΄λ μ± μ»΄ν¬λνΈμ μ μΈ
    μλλ‘μ΄λ μ± μ€νμ μν μμ  κΆν μ μ
    μλλ‘μ΄λ μ±μ΄ νμλ‘ νλ μ΅μνμ API λ λ²¨ μ μ
    μλλ‘μ΄λ μ±μ΄ νμλ‘ νλ H/W, S/W κΈ°λ₯ μ μ
    μλλ‘μ΄λ μ±μ΄ νμλ‘ νλ API λΌμ΄λΈλ¬λ¦¬ μ μ

java : ν΄λμ€λ₯Ό κ΄λ¦¬νλ ν΄λμ΄λ€. 

res : Resource ν΄λλ‘ UIμ κ΄λ ¨λ νμΌκ³Ό λμμΈ λ¦¬μμ€, λ¬Έμμ΄ λ¦¬μμ€λ₯Ό λ΄κ³  μλ ν΄λμ΄λ€.

μλλ‘μ΄λμμλ μ νλ¦¬μΌμ΄μμ λ μ΄μμμ μν΄ μ£Όλ‘ μλ° μ½λλ³΄λ€λ XML νμμ μ΄μ©νλ€.

(XML = eXtensible Markup Language. HTMLκ³Ό κ°μ λ§ν¬μ μΈμ΄)


## κ°λ° νκ²½ μ€μ 

```
# Gradle
- Gradleμ λΉλ μμ€νμ΄λ€. 

μ½κ² λ§νλ©΄,
μ°λ¦¬κ° κ°λ°ν μ½λλ₯Ό λͺ¨λ°μΌμμ μ€νν  μ μλλ‘ λ³νν΄μ£Όλ μμ€νμ΄λ€.
λν λ€λ₯Έ μ¬λμ΄ κ°λ°ν μμ€μ½λ(=dependency)λ₯Ό μ½κ² κ°μ Έμ μ¬μ©ν  μ μλ€.

κ·Έ λ°μλ νμ€νΈ, λ°°ν¬ λ± λ€μν κΈ°λ₯μ μ κ³΅νκ³  μλ€.

λΉλ μμ€νμ΄ μλ€λ©΄

λ€λ₯Έ μ¬λμ΄ κ°λ°ν λΌμ΄λΈλ¬λ¦¬λ₯Ό μ§μ  λ€μ΄λ°κ³ ,
νλ‘μ νΈμ lib ν΄λλ₯Ό λ§λ€μ΄ λ³΅μ¬νκ³ ,

λ³΅μ‘ν ν΄λμ€ ν¨μ€λ₯Ό μ€μ ν΄μ£Όμ΄μΌ νλ€.

```
- build.gradle (Project: νλ‘μ νΈλͺ)
: νλ‘μ νΈ μμ€μ Gradle μ€μ  νμΌ

    1. buildscript
    -repositories : μΈλΆ μ μ₯μ μ€μ . google()μ΄ κΈ°λ³ΈμΌλ‘ μ€μ λλ€.
    -dependencies(μμ‘΄μ±:λΌμ΄λΈλ¬λ¦¬): gradle νλ¬κ·ΈμΈ λ²μ  μ€μ 

    2. allprojects
    -repositories: μμ buildscript > repositoriesμ λμΌν μΈλΆ μ μ₯μκ° μ€μ λλ€.

    3. task
    : νλ‘μ νΈ κ³΅ν΅μ μΌλ‘ μ¬μ©ν  μμμ μ μνλ€.
    -clean(type:Delete): κΈ°λ³ΈμΌλ‘ μΆκ°λ κ³΅ν΅μμμΌλ‘, λΉλ μ μμ±λλ build λλ ν°λ¦¬λ€μ μ­μ νλ€.


- build.gradle (Module: νλ‘μ νΈλͺ.app)
: λͺ¨λ μμ€μ Gradle μ€μ  νμΌ.
λͺ¨λμ μ’λ₯λ‘λ appλͺ¨λ, μ¨μ΄λ¬λΈ λͺ¨λ, μλλ‘μ΄λ TV λͺ¨λ λ±μ΄ μλ€.
phone, tablet νλ‘μ νΈλ₯Ό μμ±νκΈ° λλ¬Έμ, κΈ°λ³Έμ μΌλ‘ app λͺ¨λ μμ€μ λΉλ μ€μ , λΌμ΄λΈλ¬λ¦¬ μ λ³΄κ° μ μ₯λλ€.

    1) plugins
    : μλλ‘μ΄λ κ°λ°μ μν νλ¬κ·ΈμΈ μ€μ  μμ­μΌλ‘, 'com.android.application'μ΄ κΈ°λ³ΈμΌλ‘ μ§μ λλ€.

    2) android
    : μ»΄νμΌ/λΉλ, λ²μ μ λ³΄, λλμ¬λΆ λ±μ μ€μ νλ€.
    : μλ λ²μ μ λ³΄ λ±μ manifest.xmlμ μ€μ νμΌλ, μ§κΈμ λͺ¨λ μμ€μ build.gradle νμΌμ μμ±νλ€.

    - compileSdkVersion: μ»΄νμΌ SDKλ²μ  μ€μ 
    - defaultConfig: κ°μ’ λ²μ  μ λ³΄ μ€μ 
    - buildTypes: λΉλ μ€μ 
    - compileOptions: μ»΄νμΌ μ€μ 

    3) dependencies
    : μΈλΆ λΌμ΄λΈλ¬λ¦¬λ₯Ό μ€μ νλ€.


- gradle-wrapper.properties(Gradle Version)
: Gradle μμ²΄μ κ΄λ ¨λ μ€μ  νμΌ

- proguard-rules.pro (ProGuard Rules for νλ‘μ νΈλͺ.app)
: μ½λ λλν λκ΅¬ μ€μ  νμΌ. 
νμν κ·μΉμ΄ μλ€λ©΄ μ΄ νμΌμ κΈ°μ νλ€.

- gradle.properties (Project Properties)
: νλ‘μ νΈ μμ€μ Gradle νκ²½ μ€μ  νμΌ

- settings.gradle (Project Settings)
: νλ‘μ νΈμ ν¬ν¨λ λͺ¨λμ λ±λ‘/κ΄λ¦¬νλ νμΌ
phone, tabletμΌλ‘ νλ‘μ νΈλ₯Ό μμ±ν κ²½μ°, app λͺ¨λλ§ κΈ°λ³ΈμΌλ‘ λ±λ‘λμ΄ μλ€.
μ¨μ΄λ¬λΈ λͺ¨λμ΄λ μλλ‘μ΄λ TVλͺ¨λμ μΆγνλ©΄ μ΄ κ³³μ λ±λ‘λλ€.

- local.properties (SDK Location)
: μλλ‘μ΄λ SDK κ²½λ‘λ₯Ό κ΄λ¦¬νλ νμΌ
μ΄μ΄λ³΄λ©΄ κ·Έλ₯ μλλ‘μ΄λ SDKκ° μ€μΉλ κ²½λ‘λ§ μ ν μλ€.

## μ€ν, λ°°ν¬

```

- μλλ‘μ΄λ μ±μ μ€ν κ³Όμ 

    κ°λ°μκ° μμ±ν JAVA μ½λκ° JAVA μ»΄νμΌλ¬μ μν΄ JAVA λ°μ΄νΈ μ½λλ‘ μ»΄νμΌ λ¨
    μλ JAVA νκ²½μμλ μ»΄νμΌλ JAVA λ°μ΄νΈ μ½λλ₯Ό JVMμ ν΅ν΄ μ€ννμ§λ§, 
    μλλ‘μ΄λλ Dalvikμ΄λΌλ λ³λμ κ°μ λ¨Έμ μμ μ€νν¨. 
    
    μ΄λ₯Ό μν΄ μλλ‘μ΄λ SDKκ° μ κ³΅νλ DEX λ³νκΈ°λ₯Ό μ΄μ©νμ¬ JAVA λ°μ΄νΈ μ½λλ₯Ό Dalvikμ μ€ν ν¬λ§·μΈ .dex νμΌλ‘ λ³νν¨.

    λ³νλ .dex νμΌκ³Ό λ¦¬μμ€ νμΌλ€μ μ€μΉν  μ μλ .apk νμΌλ‘ λ§λ€μ΄μ§. 
    λ°°ν¬ λ° μ€μΉλ₯Ό μν apk νμΌλ‘ λ§λ€μ΄μ§κΈ° μν΄μλ AAPTλΌλ κ°λ° λκ΅¬λ₯Ό μ΄μ©νκ³ , μ΄ κ³Όμ μ ν¨ν€μ§μ΄λΌκ³  ν¨.

    ν¨ν€μ§ κ³Όμ μ΄ λλ λ§λ€μ΄μ§ apk νμΌμ νλ«νΌμ μ€μΉνλ©΄ λ°νμμμ μ€νλ  μ μμ.
    μ΅μ΄ μ€μΉμ AOT μ»΄νμΌλ¬μ dex2oatλ₯Ό μ¬μ©νμ¬ λ€μ΄ν°λΈ μ½λλ‘ λ³νν ν μλλ‘μ΄λ μ€λ§νΈν°μμ μ€νν  μ μκ² ν¨.

μλλ‘μ΄λ μ νλ¦¬μΌμ΄μμ .apk νμΌ νμ₯μλ‘ ν¨ν€μ§λμ΄ λ°°ν¬λ¨.

    μλλ‘μ΄λ νλ‘μ νΈμ λν μ½λ μ»΄νμΌ μμμ΄ μνλλ©΄, JAVA νλ‘κ·Έλ¨μ .class νμΌ μμ±
    .class νμΌμ μ΄μ©νμ¬ μλλ‘μ΄λ μ€ννκ²½(Android Runtime)μ μ ν©ν .dex νμΌ μμ± / 
    μ»΄νμΌλ λ¦¬μμ€ νμΌ(XML)μ resources.arscλΌλ νμΌλ‘ μμ± / 
    μλλ‘μ΄λ μ±μ μ€μ  νκ²½μ μ μνλ AndroidManifest.xml νμΌ μμ±

    .dex νμΌ + resources.arsc + AndroidManifest.xml + μ»΄νμΌλμ§ μμ λ¦¬μμ€ νμΌ(μ΄λ―Έμ§, μμ΄μ½ νμΌ λ±) =>
    ν¨κ» ν¨ν€μ§νμ¬ .apk νμΌ μμ±

    Debug Keyλ₯Ό μ¬μ©νμ¬ .apk νμΌμ μλͺνλ Signing μμμ ν¨(.apk νμΌμ΄ νμΈμ μνμ¬ μλ³μ‘°λλ κ²μ λ°©μ§)
    Google Playμ κ°λ°λ μλλ‘μ΄λ μ±μ λ°°ν¬κ° μ€λΉλλ©΄, μμ μ Key κ°μ μ΄μ©νμ¬ Signing κ°λ₯
    Signing μμμμ μ¬μ©ν ν€κ°μ μλλ‘μ΄λ μ νλ¦¬μΌμ΄μμ μλ°μ΄νΈμμ κ°λ°μμ μλ³μ μ¬μ©λ¨
    ν¨ν€μ§λ apk νμΌμ .dex νμΌλ‘ λ³ννμ¬ 
    μ€νμ Dalvikμ΄λ ART(Android Run-Time)λΌκ³  νλ λͺ¨λ°μΌ κΈ°κΈ°μ μ ν©νλ λ°νμΈ κ°μ λ¨Έμ  μ¬μ©. 
    
    μμ¦μλ ARTλ₯Ό λν΄νΈλ‘ μ¬μ©. 
    


```
