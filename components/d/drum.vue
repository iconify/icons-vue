<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i7mf6Oe)" class="f6zfmgbkz"/><path fill="url(#iL2fw2d)" class="f6zfmgbkz"/><path fill="url(#ihtKlKd)" class="f6zfmgbkz"/><path fill="url(#i8GJOoe)" class="ny_8il67t"/><path fill="url(#ik7jhgU)" class="y5oqs_2hc"/><path fill="url(#it5zCYb)" class="sjsdj8_9y"/><path class="as-xdz9nt"/><path fill="url(#irtmEmd)" class="uc6v6tb-s"/><path class="w_w49mb4w"/><path fill="url(#iggtEYc)" class="dkgzpgbui"/><path fill="url(#iYQMmxr)" class="ypuvl04rf"/><path class="ygccbeb5k"/><g filter="url(#i3xMXxc)"><ellipse fill="url(#ixoSLty)" class="wb4m0el-y"/><ellipse fill="url(#ixBWEle)" class="wb4m0el-y"/><ellipse fill="url(#i06AyLo)" class="wb4m0el-y"/></g><g filter="url(#irfeyjb)"><path class="n5g_06b-y"/></g><g filter="url(#ilo1LDz)"><path fill="url(#iPN9Cqe)" class="g0hwvac8x"/></g><g filter="url(#iGWzE5c)"><path fill="url(#iPJkyOe)" class="c0k-rbbnh"/></g><g filter="url(#i1Ki5Ss)"><path fill="url(#iPiLPdj)" clip-rule="evenodd" class="mlvmo9bzw"/><path fill="url(#iIMtwge)" clip-rule="evenodd" class="mlvmo9bzw"/><path fill="url(#i7NblXc)" clip-rule="evenodd" class="mlvmo9bzw"/><path fill="url(#iJcCqec)" clip-rule="evenodd" class="mlvmo9bzw"/><path fill="url(#iOdFW7m)" clip-rule="evenodd" class="mlvmo9bzw"/><path fill="url(#ihLPWTb)" clip-rule="evenodd" class="mlvmo9bzw"/></g><g filter="url(#izanRCd)"><ellipse stroke="url(#i5j98hc)" class="wcu-h1buo"/></g><g filter="url(#iiEbnGe)"><path fill="url(#idX0ZQI)" class="dvvdkpb2e"/></g><path fill="url(#iKfuOue)" class="dvvdkpb2e"/><g filter="url(#i3DzrNd)"><path class="cn5xtlbpm"/></g><path fill="url(#ikOrFEU)" class="vacl7ybhk"/><path fill="url(#iLYrIAe)" class="vacl7ybhk"/><g filter="url(#iTqJNae)"><path class="n-s2vpthk"/></g><path fill="url(#i165q5d)" class="c5b7x9opc"/><path fill="url(#iu6bwSV)" class="c5b7x9opc"/><path fill="url(#isaTQ4c)" class="c5b7x9opc"/><g filter="url(#iJzJ5ae)"><path class="emft-vbsw"/></g><path fill="url(#iOy7aPm)" class="t32djtbap"/><path fill="url(#i78NsFe)" class="t32djtbap"/><g filter="url(#ihGtUkl)"><rect transform="rotate(43.887 12.703 11.933)" class="tdvbu6n5x"/></g><defs><radialGradient id="ihtKlKd" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.2091 -10.3073 0 15.925 14.14)" gradientUnits="userSpaceOnUse"><stop offset=".85" class="jb9-guben"/><stop offset="1" class="fg-q6db_j"/></radialGradient><radialGradient id="ixoSLty" cx="0" cy="0" r="1" gradientTransform="matrix(9.53575 9.83608 -8.86135 8.59078 10.387 8.035)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="bnvazacin"/><stop offset="1" class="law12d9xd"/></radialGradient><radialGradient id="ixBWEle" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.1776 -13.0978 0 15.9 10.44)" gradientUnits="userSpaceOnUse"><stop offset=".674" class="a3doun7rm"/><stop offset="1" class="rqrvvqkqm"/></radialGradient><radialGradient id="i06AyLo" cx="0" cy="0" r="1" gradientTransform="rotate(53.625 -4.883 21.617)scale(9.55863 9.86984)" gradientUnits="userSpaceOnUse"><stop offset=".809" class="oyvhw2svk"/><stop offset=".975" class="oy39az3kg"/></radialGradient><radialGradient id="iPJkyOe" cx="0" cy="0" r="1" gradientTransform="rotate(-71.168 26.912 6.371)scale(9.11912 18.5955)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="bx4nlsbox"/><stop offset="1" class="qczabzb8i"/></radialGradient><radialGradient id="iIMtwge" cx="0" cy="0" r="1" gradientTransform="matrix(10.11266 -4.71445 4.8298 10.3601 15.005 14.318)" gradientUnits="userSpaceOnUse"><stop offset=".868" class="egb3l0b8d"/><stop offset=".98" class="qxgncwd8k"/></radialGradient><radialGradient id="i7NblXc" cx="0" cy="0" r="1" gradientTransform="rotate(40.601 -5.394 16.456)scale(1.73062 5.29515)" gradientUnits="userSpaceOnUse"><stop class="gxvbk1fbl"/><stop offset="1" class="juvb86bfc"/></radialGradient><radialGradient id="iJcCqec" cx="0" cy="0" r="1" gradientTransform="rotate(127.776 1.713 6.963)scale(1.89988 8.29046)" gradientUnits="userSpaceOnUse"><stop class="jtn-vpbrl"/><stop offset="1" class="hhv5q8bha"/></radialGradient><radialGradient id="iOdFW7m" cx="0" cy="0" r="1" gradientTransform="rotate(-132.51 13.414 -.837)scale(1.22229 3.77066)" gradientUnits="userSpaceOnUse"><stop offset=".009" class="b6__dbifj"/><stop offset="1" class="bw_qsry_s"/></radialGradient><radialGradient id="ihLPWTb" cx="0" cy="0" r="1" gradientTransform="matrix(2.4472 -7.34155 8.1297 2.7099 16.66 12.807)" gradientUnits="userSpaceOnUse"><stop offset=".816" class="dpxi3jbrr"/><stop offset=".972" class="qg-oh7b7r"/></radialGradient><radialGradient id="iKfuOue" cx="0" cy="0" r="1" gradientTransform="rotate(136.302 14.188 7.47)scale(1.55262 1.84294)" gradientUnits="userSpaceOnUse"><stop class="ekqlapnnu"/><stop offset="1" class="a_zqds5lv"/></radialGradient><radialGradient id="ikOrFEU" cx="0" cy="0" r="1" gradientTransform="rotate(-135.931 6.046 2.58)scale(8.82917 6.01608)" gradientUnits="userSpaceOnUse"><stop offset=".878" class="xpp9s21ph"/><stop offset=".975" class="qsmeodbsc"/></radialGradient><radialGradient id="iLYrIAe" cx="0" cy="0" r="1" gradientTransform="rotate(-115.301 9.78 2.924)scale(1.90112 3.71029)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="zkhbzltam"/><stop offset="1" class="sxf2udbyr"/></radialGradient><radialGradient id="i165q5d" cx="0" cy="0" r="1" gradientTransform="matrix(-.0625 -1.3517 1.8939 -.08757 13.44 15.24)" gradientUnits="userSpaceOnUse"><stop class="kt00vwb9m"/><stop offset="1" class="ja-11nbrw"/></radialGradient><radialGradient id="isaTQ4c" cx="0" cy="0" r="1" gradientTransform="rotate(-134.519 10.099 4.28)scale(3.96672 4.03388)" gradientUnits="userSpaceOnUse"><stop offset=".697" class="qu-qopbwm"/><stop offset="1" class="hvj5e-b3w"/></radialGradient><radialGradient id="iOy7aPm" cx="0" cy="0" r="1" gradientTransform="matrix(.24945 -1.7212 1.7931 .25987 18.157 15.667)" gradientUnits="userSpaceOnUse"><stop class="v52i2997f"/><stop offset="1" class="xqcwg16yx"/></radialGradient><radialGradient id="i78NsFe" cx="0" cy="0" r="1" gradientTransform="rotate(135.641 7.536 10.302)scale(1.50026 1.732)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="cum9xbb9z"/><stop offset="1" class="udcaedced"/></radialGradient><linearGradient id="i7mf6Oe" x1="23.121" x2="10.199" y1="23.948" y2="23.948" gradientUnits="userSpaceOnUse"><stop class="qdc59d5gc"/><stop offset="1" class="rmslf4blj"/></linearGradient><linearGradient id="iL2fw2d" x1="5.51" x2="12.195" y1="18.91" y2="18.91" gradientUnits="userSpaceOnUse"><stop offset=".104" class="c4gwknbud"/><stop offset="1" class="e8hkgkaqb"/></linearGradient><linearGradient id="i8GJOoe" x1="8.565" x2="9.854" y1="23.795" y2="23.795" gradientUnits="userSpaceOnUse"><stop class="ptginybcu"/><stop offset="1" class="fndradcny"/></linearGradient><linearGradient id="ik7jhgU" x1="15.534" x2="16.823" y1="24.779" y2="24.779" gradientUnits="userSpaceOnUse"><stop class="crb1mstai"/><stop offset="1" class="gxfjm7bza"/></linearGradient><linearGradient id="it5zCYb" x1="22.503" x2="24.003" y1="23.795" y2="23.795" gradientUnits="userSpaceOnUse"><stop class="vti6sxbhl"/><stop offset="1" class="xcyhljb2o"/></linearGradient><linearGradient id="irtmEmd" x1="8.042" x2="9.51" y1="27.638" y2="28.577" gradientUnits="userSpaceOnUse"><stop class="y2pwd8b3j"/><stop offset="1" class="ssk3x6boh"/></linearGradient><linearGradient id="iggtEYc" x1="8.042" x2="9.628" y1="21.545" y2="22.42" gradientUnits="userSpaceOnUse"><stop class="y2pwd8b3j"/><stop offset="1" class="ssk3x6boh"/></linearGradient><linearGradient id="iYQMmxr" x1="15.917" x2="15.917" y1="23.389" y2="25.17" gradientUnits="userSpaceOnUse"><stop offset=".246" class="xhgsjf2il"/><stop offset="1" class="d2xpkdbkt"/></linearGradient><linearGradient id="iPN9Cqe" x1="17.182" x2="23.189" y1="14.755" y2="8.111" gradientUnits="userSpaceOnUse"><stop class="wt1kp6hyj"/><stop offset="1" class="lnhi0l9vu"/></linearGradient><linearGradient id="iPiLPdj" x1="15.917" x2="15.917" y1="4.139" y2="23.616" gradientUnits="userSpaceOnUse"><stop class="a2qkpsbto"/><stop offset="1" class="e2sumdpne"/></linearGradient><linearGradient id="i5j98hc" x1="9.113" x2="13.901" y1="18.953" y2="13.961" gradientUnits="userSpaceOnUse"><stop class="hxfptjboc"/><stop offset="1" class="aofzk-19c"/></linearGradient><linearGradient id="idX0ZQI" x1="23.865" x2="24.991" y1="7.172" y2="8.598" gradientUnits="userSpaceOnUse"><stop class="l-lkog0kb"/><stop offset="1" class="qoe6gdc1t"/></linearGradient><linearGradient id="iu6bwSV" x1="14.159" x2="13.346" y1="12.202" y2="13.045" gradientUnits="userSpaceOnUse"><stop class="jz4a20bwu"/><stop offset="1" class="ce-q0rbkl"/></linearGradient><filter id="i3xMXxc" width="15.859" height="15.367" x="7.846" y="6.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.662745 0 0 0 0 0.690196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18924"/></filter><filter id="irfeyjb" width="8.748" height="9.241" x="6.184" y="8.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18924" stdDeviation=".75"/></filter><filter id="ilo1LDz" width="10.084" height="10.613" x="14.417" y="6.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18924" stdDeviation=".75"/></filter><filter id="iGWzE5c" width="19.95" height="9.883" x="5.942" y="20.412" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.533333 0 0 0 0 0.839216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18924"/></filter><filter id="i1Ki5Ss" width="20.053" height="19.577" x="5.94" y="4.039" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.631373 0 0 0 0 0.54902 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18924"/></filter><filter id="izanRCd" width="17.832" height="17.308" x="7.084" y="5.308" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18924" stdDeviation=".2"/></filter><filter id="iiEbnGe" width="11.032" height="11.019" x="18.993" y="2.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.588235 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18924"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.682353 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_18924" result="effect2_innerShadow_18_18924"/></filter><filter id="i3DzrNd" width="11.232" height="11.219" x="1.709" y="2.248" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.556863 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18924"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.917647 0 0 0 0 0.72549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_18924" result="effect2_innerShadow_18_18924"/></filter><filter id="iTqJNae" width="3.853" height="3.836" x="11.116" y="11.405" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.545098 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18924"/></filter><filter id="iJzJ5ae" width="4.003" height="3.986" x="17.115" y="11.255" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.533333 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18924"/></filter><filter id="ihGtUkl" width="3.172" height="3.123" x="11.763" y="11.478" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18924" stdDeviation=".3"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:drum" /></template>
<style>
.a_zqds5lv {
  stop-color: var(--svg-color--ffc7a6, #FFC7A6);
  stop-opacity: 0;
}

.a2qkpsbto {
  stop-color: var(--svg-color--cbc2c8, #CBC2C8);
}

.a3doun7rm {
  stop-color: var(--svg-color--ffe4e3, #FFE4E3);
  stop-opacity: 0;
}

.aofzk-19c {
  stop-color: var(--svg-color--e6dce6, #E6DCE6);
  stop-opacity: 0;
}

.as-xdz9nt {
  fill: var(--svg-color--f3b050, #F3B050);
  d: path("M23.792 26.445a10 10 0 0 1-1.762 1.759a.9.9 0 0 1-.05-.3v-2.593a.906.906 0 0 1 1.812 0z");
}

.b6__dbifj {
  stop-color: var(--svg-color--a69690, #A69690);
}

.bnvazacin {
  stop-color: var(--svg-color--ffe4d8, #FFE4D8);
}

.bw_qsry_s {
  stop-color: var(--svg-color--b9aca8, #B9ACA8);
  stop-opacity: 0;
}

.bx4nlsbox {
  stop-color: var(--svg-color--b791d7, #B791D7);
}

.c0k-rbbnh {
  d: path("M5.942 20.512c.103 5.42 4.53 9.783 9.975 9.783s9.871-4.362 9.975-9.783c-.81 4.711-4.968 8.299-9.975 8.299c-5.008 0-9.166-3.588-9.975-8.299");
}

.c4gwknbud {
  stop-color: var(--svg-color--c8615d, #C8615D);
}

.c5b7x9opc {
  d: path("M13.282 12.02a1.273 1.273 0 0 0-1.787 1.815l1.057 1.04a1.273 1.273 0 0 0 1.786-1.814z");
}

.ce-q0rbkl {
  stop-color: var(--svg-color--ffdda8, #FFDDA8);
  stop-opacity: 0;
}

.cn5xtlbpm {
  fill: var(--svg-color--fec0a1, #FEC0A1);
  d: path("M3.775 2.83a1.05 1.05 0 1 0-1.483 1.486l9.516 8.901l.883-.898z");
}

.crb1mstai {
  stop-color: var(--svg-color--ba97d9, #BA97D9);
}

.cum9xbb9z {
  stop-color: var(--svg-color--ffe5b0, #FFE5B0);
}

.d2xpkdbkt {
  stop-color: var(--svg-color--d88e50, #D88E50);
}

.dkgzpgbui {
  d: path("M8.042 18.702a.906.906 0 1 1 1.812 0v2.593a.906.906 0 1 1-1.812 0z");
}

.dpxi3jbrr {
  stop-color: var(--svg-color--b2969f, #B2969F);
}

.dvvdkpb2e {
  d: path("M28.058 2.83a1.05 1.05 0 1 1 1.484 1.486l-9.516 8.901l-.883-.898z");
}

.e2sumdpne {
  stop-color: var(--svg-color--d4c9de, #D4C9DE);
}

.e8hkgkaqb {
  stop-color: var(--svg-color--c8615d, #C8615D);
  stop-opacity: 0;
}

.egb3l0b8d {
  stop-color: var(--svg-color--d9c9d6, #D9C9D6);
  stop-opacity: 0;
}

.ekqlapnnu {
  stop-color: var(--svg-color--ffe6b8, #FFE6B8);
}

.emft-vbsw {
  fill: var(--svg-color--ffbb98, #FFBB98);
  d: path("M18.552 12.02a1.273 1.273 0 0 1 1.786 1.815l-1.057 1.04a1.273 1.273 0 0 1-1.786-1.814z");
}

.f6zfmgbkz {
  d: path("M5.94 14.138h19.953v6.18c0 5.51-4.466 9.977-9.976 9.977S5.94 25.83 5.94 20.32z");
}

.fg-q6db_j {
  stop-color: var(--svg-color--db2156, #DB2156);
  stop-opacity: 0;
}

.fndradcny {
  stop-color: var(--svg-color--c19ed7, #C19ED7);
}

.ft5dv1b6b {
  fill: none;
}

.g0hwvac8x {
  d: path("M23.001 9.95c-.172-.572-.384-1.1-.602-1.563l-3.862 4.06a1.27 1.27 0 0 0-1.184.333l-1.056 1.04a1.273 1.273 0 0 0 1.786 1.814l1.056-1.04c.336-.33.45-.802.34-1.227z");
}

.gxfjm7bza {
  stop-color: var(--svg-color--cca9ed, #CCA9ED);
}

.gxvbk1fbl {
  stop-color: var(--svg-color--dfd1ca, #DFD1CA);
}

.hhv5q8bha {
  stop-color: var(--svg-color--b29eaf, #B29EAF);
  stop-opacity: 0;
}

.hvj5e-b3w {
  stop-color: var(--svg-color--e2a46f, #E2A46F);
}

.hxfptjboc {
  stop-color: var(--svg-color--e6dce6, #E6DCE6);
}

.ja-11nbrw {
  stop-color: var(--svg-color--db8583, #DB8583);
  stop-opacity: 0;
}

.jb9-guben {
  stop-color: var(--svg-color--db2156, #DB2156);
}

.jtn-vpbrl {
  stop-color: var(--svg-color--9b7d91, #9B7D91);
}

.juvb86bfc {
  stop-color: var(--svg-color--dfd1ca, #DFD1CA);
  stop-opacity: 0;
}

.jz4a20bwu {
  stop-color: var(--svg-color--ffdda8, #FFDDA8);
}

.kt00vwb9m {
  stop-color: var(--svg-color--db8583, #DB8583);
}

.l-lkog0kb {
  stop-color: var(--svg-color--ebb589, #EBB589);
}

.law12d9xd {
  stop-color: var(--svg-color--fed8d0, #FED8D0);
}

.lnhi0l9vu {
  stop-color: var(--svg-color--d6ada7, #D6ADA7);
}

.mlvmo9bzw {
  fill-rule: evenodd;
  d: path("M25.893 14.057c0 5.34-4.638 9.559-9.992 9.559s-9.96-4.299-9.96-9.638S10.546 4.14 15.9 4.14s9.992 4.219 9.992 9.918M15.9 21.617c4.31 0 7.805-3.384 7.805-7.559c0-4.174-3.494-7.558-7.805-7.558c-4.31 0-7.805 3.384-7.805 7.558c0 4.175 3.495 7.559 7.805 7.559");
}

.n-s2vpthk {
  fill: var(--svg-color--fdb595, #FDB595);
  d: path("M13.282 12.02a1.273 1.273 0 0 0-1.787 1.815l1.057 1.04a1.273 1.273 0 0 0 1.786-1.814z");
}

.n5g_06b-y {
  fill: var(--svg-color--d3a1ac, #D3A1AC);
  d: path("M7.684 11.66c.172-.572.384-1.1.602-1.563l2.526 2.688c.41-.096.86.014 1.183.332l1.057 1.04a1.273 1.273 0 0 1-1.786 1.815l-1.057-1.04a1.27 1.27 0 0 1-.34-1.227z");
}

.ny_8il67t {
  d: path("M9.854 28.243a10 10 0 0 1-1.812-1.798v-6.743h1.812z");
}

.oy39az3kg {
  stop-color: var(--svg-color--d2aba8, #D2ABA8);
}

.oyvhw2svk {
  stop-color: var(--svg-color--f9d6d5, #F9D6D5);
  stop-opacity: 0;
}

.ptginybcu {
  stop-color: var(--svg-color--b497bf, #B497BF);
}

.qczabzb8i {
  stop-color: var(--svg-color--d3c4e2, #D3C4E2);
}

.qdc59d5gc {
  stop-color: var(--svg-color--f1469c, #F1469C);
}

.qg-oh7b7r {
  stop-color: var(--svg-color--b2969f, #B2969F);
  stop-opacity: 0;
}

.qoe6gdc1t {
  stop-color: var(--svg-color--f5ad8e, #F5AD8E);
}

.qsmeodbsc {
  stop-color: var(--svg-color--d7ae81, #D7AE81);
}

.qu-qopbwm {
  stop-color: var(--svg-color--e2a46f, #E2A46F);
  stop-opacity: 0;
}

.qxgncwd8k {
  stop-color: var(--svg-color--f7eef3, #F7EEF3);
}

.rmslf4blj {
  stop-color: var(--svg-color--cb235c, #CB235C);
}

.rqrvvqkqm {
  stop-color: var(--svg-color--ffe4e3, #FFE4E3);
}

.sjsdj8_9y {
  d: path("M23.792 26.445a10 10 0 0 1-1.813 1.798v-8.541h1.813z");
}

.ssk3x6boh {
  stop-color: var(--svg-color--cd8a4c, #CD8A4C);
}

.sxf2udbyr {
  stop-color: var(--svg-color--e39472, #E39472);
  stop-opacity: 0;
}

.t32djtbap {
  d: path("M18.552 12.02a1.273 1.273 0 0 1 1.786 1.815l-1.057 1.04a1.273 1.273 0 0 1-1.786-1.814z");
}

.tdvbu6n5x {
  width: 2.465px;
  height: 0.698px;
  x: 12.703px;
  y: 11.933px;
  fill: var(--svg-color--ffe2af, #FFE2AF);
  rx: 0.349px;
}

.uc6v6tb-s {
  d: path("M9.804 28.204a10 10 0 0 1-1.762-1.759v-1.134a.906.906 0 0 1 1.812 0v2.594a.9.9 0 0 1-.05.299");
}

.udcaedced {
  stop-color: var(--svg-color--fdc596, #FDC596);
  stop-opacity: 0;
}

.v52i2997f {
  stop-color: var(--svg-color--da8181, #DA8181);
}

.vacl7ybhk {
  d: path("M3.775 2.83a1.05 1.05 0 1 0-1.483 1.486l9.516 8.901l.883-.898z");
}

.vti6sxbhl {
  stop-color: var(--svg-color--cab4e1, #CAB4E1);
}

.w_w49mb4w {
  fill: var(--svg-color--f1b14c, #F1B14C);
  d: path("M21.98 18.702a.906.906 0 0 1 1.812 0v2.593a.906.906 0 1 1-1.813 0z");
}

.wb4m0el-y {
  cx: 15.901px;
  cy: 14.057px;
  rx: 7.805px;
  ry: 7.559px;
}

.wcu-h1buo {
  cx: 16px;
  cy: 13.961px;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  rx: 8.316px;
  ry: 8.054px;
}

.wt1kp6hyj {
  stop-color: var(--svg-color--daa9b3, #DAA9B3);
}

.xcyhljb2o {
  stop-color: var(--svg-color--e5d1f9, #E5D1F9);
}

.xhgsjf2il {
  stop-color: var(--svg-color--e5a148, #E5A148);
}

.xpp9s21ph {
  stop-color: var(--svg-color--d7ae81, #D7AE81);
  stop-opacity: 0;
}

.xqcwg16yx {
  stop-color: var(--svg-color--d58b6a, #D58B6A);
  stop-opacity: 0;
}

.y2pwd8b3j {
  stop-color: var(--svg-color--ce9051, #CE9051);
}

.y5oqs_2hc {
  d: path("M16.823 30.255a10 10 0 0 1-1.812 0V19.702h1.812z");
}

.ygccbeb5k {
  fill: var(--svg-color--db8f4f, #DB8F4F);
  d: path("M16.823 30.255a10 10 0 0 1-1.812 0v-1.897a.906.906 0 1 1 1.812 0z");
}

.ypuvl04rf {
  d: path("M15.01 21.67a.906.906 0 1 1 1.813 0v2.594a.906.906 0 1 1-1.812 0z");
}

.zkhbzltam {
  stop-color: var(--svg-color--e39472, #E39472);
}

</style>
