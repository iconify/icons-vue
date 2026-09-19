<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i33ovga)" class="taj1jgbfl"/><g filter="url(#ic5Xw9c)"><path fill="url(#if2YnkL)" class="n-c7wwb5q"/></g><path fill="url(#icNbVZc)" class="n-c7wwb5q"/><path class="zqw2376vi"/><path fill="url(#iH6T4Dd)" class="a16id7p3k"/><path fill="url(#iIAUSJb)" class="a16id7p3k"/><path class="xrux4ni3c"/><path fill="url(#iLMThXb)" class="oskfltbrz"/><path fill="url(#iI5RUGc)" class="oskfltbrz"/><path fill="url(#iwu5Zec)" class="oskfltbrz"/><path class="xfk6amb8v"/><path fill="url(#i7OCkvN)" class="y01kc3b8i"/><path fill="url(#ieO86yL)" class="y01kc3b8i"/><path class="c8_be_bja"/><path fill="url(#iV45z3d)" class="yvl4y2bse"/><path fill="url(#iOgIzGb)" class="yvl4y2bse"/><path fill="url(#ibF8JCb)" class="yvl4y2bse"/><path fill="url(#iA9a2Le)" class="yvl4y2bse"/><path fill="url(#iWF6mYb)" class="yvl4y2bse"/><path fill="url(#izhsPLz)" class="yvl4y2bse"/><path fill="url(#iAP9fAc)" class="yvl4y2bse"/><path fill="url(#iBSAMmd)" class="yvl4y2bse"/><path fill="url(#iCEENYc)" class="yvl4y2bse"/><g filter="url(#i9c1sBd)"><path class="sr-f_tbjn"/></g><path class="h1t1vibrh"/><path fill="url(#irH69rK)" class="znh-hdc4k"/><path fill="url(#ig4gxOu)" class="znh-hdc4k"/><path fill="url(#iwC24Jd)" class="gihuc0b-f"/><path class="nid9_0tuv"/><path fill="url(#iuqpNCc)" class="t2colpbsg"/><path fill="url(#iF78w2G)" class="t2colpbsg"/><path fill="url(#iYUYUHc)" class="t2colpbsg"/><g filter="url(#i8kF3Ae)"><path fill="url(#i9Adi5d)" class="tyu38-e5w"/><path fill="url(#i5Yl5ve)" class="tyu38-e5w"/><path fill="url(#iTPOhyc)" class="tyu38-e5w"/><path fill="url(#iphbJ0d)" class="tyu38-e5w"/><path fill="url(#iyrCHLd)" class="tyu38-e5w"/><path fill="url(#iGeT3jd)" class="tyu38-e5w"/><path fill="url(#ioCZ3Oe)" class="tyu38-e5w"/></g><g filter="url(#iW2v9hA)"><path class="ri9i1ztjv"/></g><g filter="url(#iBSrohd)"><path class="b_bav6i8x"/></g><g filter="url(#ix1w8ne)"><path stroke="url(#iQrxbfy)" class="x8mnt0d2r"/></g><g filter="url(#ioJIqbc)"><path stroke="url(#i3NEYdc)" class="ait0hwb3w"/></g><g class="mc2zb0bvp"><path fill="url(#itPHc6i)" class="gvgwa7ijg"/><path fill="url(#i1veCBD)" class="gvgwa7ijg"/><path fill="url(#iZwaUtd)" class="gvgwa7ijg"/><path fill="url(#iYGNaZd)" class="gvgwa7ijg"/></g><g filter="url(#i3p3ayc)"><path stroke="url(#i2SUx6f)" class="nw-wxtb6l"/></g><defs><radialGradient id="icNbVZc" cx="0" cy="0" r="1" gradientTransform="matrix(.34375 2.8125 -6.93477 .84759 27.906 12.813)" gradientUnits="userSpaceOnUse"><stop class="q9umy0b_q"/><stop offset="1" class="ecfxhclsg"/></radialGradient><radialGradient id="iIAUSJb" cx="0" cy="0" r="1" gradientTransform="matrix(2.07812 -3.35938 5.3031 3.2805 15.922 28.578)" gradientUnits="userSpaceOnUse"><stop offset=".645" class="h-9mxf4ip"/><stop offset="1" class="l-3kk-jhn"/></radialGradient><radialGradient id="iwu5Zec" cx="0" cy="0" r="1" gradientTransform="matrix(.84937 0 0 1.67187 14.64 27.875)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="uzf94jp_m"/><stop offset=".809" class="x6q59gjjw"/></radialGradient><radialGradient id="iV45z3d" cx="0" cy="0" r="1" gradientTransform="matrix(-.375 19.68753 -27.74017 -.52838 17.375 6.375)" gradientUnits="userSpaceOnUse"><stop offset=".72" class="jpyr-2r-q"/><stop offset="1" class="up-6wl8dn"/></radialGradient><radialGradient id="iOgIzGb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.40625 1.34376 -2.23056 -3.99422 18.156 22.156)" gradientUnits="userSpaceOnUse"><stop class="m0p6scoik"/><stop offset="1" class="pqln2p5ve"/></radialGradient><radialGradient id="ibF8JCb" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 -2.3125 1.97058 2.66294 13.5 5.688)" gradientUnits="userSpaceOnUse"><stop class="n0mo5ylhv"/><stop offset="1" class="v76lrjbcu"/></radialGradient><radialGradient id="iA9a2Le" cx="0" cy="0" r="1" gradientTransform="matrix(-2.24997 3.87501 -1.55703 -.90407 10.375 9.813)" gradientUnits="userSpaceOnUse"><stop class="o16_3abrg"/><stop offset="1" class="via_oubyr"/></radialGradient><radialGradient id="iWF6mYb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.34376 -1.87497 1.7523 -3.125 18.656 17.625)" gradientUnits="userSpaceOnUse"><stop offset=".058" class="ox-6_8b4t"/><stop offset="1" class="gehzaab4q"/></radialGradient><radialGradient id="izhsPLz" cx="0" cy="0" r="1" gradientTransform="rotate(-30.964 47.46 -25.302)scale(2.55104 1.98295)" gradientUnits="userSpaceOnUse"><stop offset=".058" class="ox-6_8b4t"/><stop offset="1" class="gehzaab4q"/></radialGradient><radialGradient id="iAP9fAc" cx="0" cy="0" r="1" gradientTransform="matrix(7.9375 -4.3125 6.58084 12.11253 4.625 22)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="s5_1en1fk"/><stop offset=".591" class="fni_88bln"/></radialGradient><radialGradient id="iBSAMmd" cx="0" cy="0" r="1" gradientTransform="rotate(125.2 4.249 9.319)scale(4.93334 1.47335)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="ij45wmb6b"/><stop offset="1" class="vpg3ucb1n"/></radialGradient><radialGradient id="iCEENYc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.03126 2.53123 -.75596 -1.5026 16.563 11.156)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="ij45wmb6b"/><stop offset="1" class="vpg3ucb1n"/></radialGradient><radialGradient id="irH69rK" cx="0" cy="0" r="1" gradientTransform="matrix(4.78978 -6.3125 5.512 4.18238 7.96 11.875)" gradientUnits="userSpaceOnUse"><stop class="qtmmk-biq"/><stop offset="1" class="oi1lpacrg"/></radialGradient><radialGradient id="ig4gxOu" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 1.375 -.85876 1.95173 5.25 4.125)" gradientUnits="userSpaceOnUse"><stop class="l_n6ri8oc"/><stop offset="1" class="ga4joklrv"/></radialGradient><radialGradient id="iYUYUHc" cx="0" cy="0" r="1" gradientTransform="rotate(-174.496 3.026 3.99)scale(3.67319 3.78303)" gradientUnits="userSpaceOnUse"><stop offset=".874" class="a2rrn1bfg"/><stop offset="1" class="gzcz9plvc"/></radialGradient><radialGradient id="i5Yl5ve" cx="0" cy="0" r="1" gradientTransform="matrix(0 -12.1875 7.21041 0 18.563 26.063)" gradientUnits="userSpaceOnUse"><stop offset=".574" class="z2o935btm"/><stop offset=".938" class="aius0j5bh"/></radialGradient><radialGradient id="iTPOhyc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.25 .625 -.5133 -1.84787 22.469 20.234)" gradientUnits="userSpaceOnUse"><stop class="th_gchbom"/><stop offset="1" class="vlbfw8bfy"/></radialGradient><radialGradient id="iphbJ0d" cx="0" cy="0" r="1" gradientTransform="rotate(135.712 6.889 13.549)scale(6.22081 7.73935)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="g1-68ybmr"/><stop offset="1" class="ux9wxdawy"/></radialGradient><radialGradient id="iyrCHLd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.8125 1.18752 -.62736 -1.48581 21.531 19.969)" gradientUnits="userSpaceOnUse"><stop class="ux9wxdawy"/><stop offset="1" class="g1-68ybmr"/></radialGradient><radialGradient id="iGeT3jd" cx="0" cy="0" r="1" gradientTransform="rotate(134.04 6.862 15.206)scale(1.97797 .7291)" gradientUnits="userSpaceOnUse"><stop class="u05lukb9u"/><stop offset="1" class="g1-68ybmr"/></radialGradient><radialGradient id="ioCZ3Oe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.5 2.5 0 19.5 24.125)" gradientUnits="userSpaceOnUse"><stop class="y6fg1wbjg"/><stop offset="1" class="mykl90e_w"/></radialGradient><radialGradient id="itPHc6i" cx="0" cy="0" r="1" gradientTransform="matrix(1.60938 0 0 3.61983 18.297 26.125)" gradientUnits="userSpaceOnUse"><stop class="kp85l4ben"/><stop offset="1" class="u0dgppboj"/></radialGradient><radialGradient id="i1veCBD" cx="0" cy="0" r="1" gradientTransform="rotate(-131.272 17.296 7.88)scale(3.90841 3.47203)" gradientUnits="userSpaceOnUse"><stop class="cr8gwobax"/><stop offset="1" class="hze5bs0rc"/></radialGradient><radialGradient id="iYGNaZd" cx="0" cy="0" r="1" gradientTransform="rotate(-41.821 41.935 -10.585)scale(2.29639 .99754)" gradientUnits="userSpaceOnUse"><stop class="pyli1tb4h"/><stop offset=".646" class="cnc4zrbkq"/></radialGradient><linearGradient id="i33ovga" x1="24.5" x2="29.25" y1="14.813" y2="12.938" gradientUnits="userSpaceOnUse"><stop class="je5ihcbnd"/><stop offset="1" class="yzk018vul"/></linearGradient><linearGradient id="if2YnkL" x1="27.5" x2="27.5" y1="13" y2="21.006" gradientUnits="userSpaceOnUse"><stop class="tvsrpdltd"/><stop offset="1" class="ogcd6k74i"/></linearGradient><linearGradient id="iH6T4Dd" x1="13.859" x2="16.328" y1="27" y2="27" gradientUnits="userSpaceOnUse"><stop class="gsi1nvbgo"/><stop offset="1" class="qhtmvobwn"/></linearGradient><linearGradient id="iLMThXb" x1="16.927" x2="16.209" y1="27.344" y2="29.063" gradientUnits="userSpaceOnUse"><stop class="g8eva8vyf"/><stop offset="1" class="sh1k17b4x"/></linearGradient><linearGradient id="iI5RUGc" x1="16.209" x2="16.209" y1="30.297" y2="29.656" gradientUnits="userSpaceOnUse"><stop class="g8eva8vyf"/><stop offset="1" class="sh1k17b4x"/></linearGradient><linearGradient id="i7OCkvN" x1="19.5" x2="19.5" y1="27.156" y2="28.172" gradientUnits="userSpaceOnUse"><stop class="blrq84bds"/><stop offset="1" class="n9i8a1bqy"/></linearGradient><linearGradient id="ieO86yL" x1="19.5" x2="19.5" y1="30.281" y2="29.625" gradientUnits="userSpaceOnUse"><stop class="blrq84bds"/><stop offset="1" class="n9i8a1bqy"/></linearGradient><linearGradient id="iwC24Jd" x1="9.581" x2="9.581" y1="5.8" y2="7.244" gradientUnits="userSpaceOnUse"><stop offset=".006" class="aoo6bub-i"/><stop offset="1" class="vuad6pb7r"/></linearGradient><linearGradient id="iuqpNCc" x1="4.969" x2="5" y1="12.219" y2="8.844" gradientUnits="userSpaceOnUse"><stop offset=".138" class="h39-kzb5n"/><stop offset="1" class="f9xkwoapo"/></linearGradient><linearGradient id="iF78w2G" x1="4" x2="4.5" y1="3.828" y2="5.672" gradientUnits="userSpaceOnUse"><stop offset=".143" class="h39-kzb5n"/><stop offset="1" class="f9xkwoapo"/></linearGradient><linearGradient id="i9Adi5d" x1="19.107" x2="19.107" y1="24" y2="19.317" gradientUnits="userSpaceOnUse"><stop class="t53t9pbnf"/><stop offset="1" class="zlhreg8au"/></linearGradient><linearGradient id="iQrxbfy" x1="16.951" x2="18.844" y1="29.719" y2="29.719" gradientUnits="userSpaceOnUse"><stop class="eatsizbuc"/><stop offset="1" class="h2_c79j8v"/><stop offset="1" class="h2_c79j8v"/></linearGradient><linearGradient id="i3NEYdc" x1="12.844" x2="14.781" y1="29.734" y2="29.734" gradientUnits="userSpaceOnUse"><stop class="eatsizbuc"/><stop offset="1" class="h2_c79j8v"/></linearGradient><linearGradient id="iZwaUtd" x1="20.035" x2="20.035" y1="26.547" y2="27.313" gradientUnits="userSpaceOnUse"><stop offset=".014" class="wwimjchyj"/><stop offset="1" class="q99c3li_e"/></linearGradient><linearGradient id="i2SUx6f" x1="11.531" x2="13.531" y1="13.594" y2="9.969" gradientUnits="userSpaceOnUse"><stop class="px0djmbvk"/><stop offset="1" class="z_1mb4bjp"/></linearGradient><filter id="ic5Xw9c" width="5" height="8.155" x="25" y="12.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.560784 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_5078"/></filter><filter id="i9c1sBd" width="17.151" height="8.516" x="9.594" y="10.374" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5078" stdDeviation="1.25"/></filter><filter id="i8kF3Ae" width="7.357" height="8.626" x="15.34" y="15.004" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.627451 0 0 0 0 0.662745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_5078"/></filter><filter id="iW2v9hA" width="2.756" height="1.041" x="20.203" y="28.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5078" stdDeviation=".125"/></filter><filter id="iBSrohd" width="1.25" height="2.672" x="19.867" y="26.859" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5078" stdDeviation=".25"/></filter><filter id="ix1w8ne" width="2.609" height=".65" x="16.594" y="29.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5078" stdDeviation=".125"/></filter><filter id="ioJIqbc" width="3.328" height=".65" x="12.391" y="29.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5078" stdDeviation=".125"/></filter><filter id="i3p3ayc" width="6.634" height="8.307" x="8.677" y="7.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5078" stdDeviation=".625"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:dodo" /></template>
<style>
.a16id7p3k {
  d: path("M17.06 27h-2.12c-.52 0-.94-.42-.94-.94V23h4v3.06c0 .52-.42.94-.94.94");
}

.a2rrn1bfg {
  stop-color: var(--svg-color--ffe395, #FFE395);
  stop-opacity: 0;
}

.ait0hwb3w {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.64 29.469h2.829");
}

.aius0j5bh {
  stop-color: var(--svg-color--9d9ca4, #9D9CA4);
}

.aoo6bub-i {
  stop-color: var(--svg-color--513468, #513468);
}

.b_bav6i8x {
  stroke: var(--svg-color--ffc770, #FFC770);
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M20.492 29.031V27.36");
}

.blrq84bds {
  stop-color: var(--svg-color--ff9339, #FF9339);
}

.c8_be_bja {
  fill: var(--svg-color--adaab5, #ADAAB5);
  d: path("M11.47 2a4.38 4.38 0 0 0-3.24 7.31h3.05v.07l-.63.12l-2.68 4.67A7.5 7.5 0 0 0 7 17.84C7 21.79 10.21 25 14.16 25h3.49a.35.35 0 0 1 .35.35v.71c0 .52.42.94.94.94h2.12c.52 0 .94-.42.94-.94v-.75a.31.31 0 0 1 .31-.31C24.9 25 27 22.9 27 20.31v-2.88c0-.99-.43-1.93-1.19-2.57c-2.12-1.8-4.82-2.97-7.81-2.97c-1.61 0-3.14.31-4.55.87c-.29.11-.55-.2-.4-.46l2.19-3.64c.43-.7.66-1.54.63-2.43c-.08-2.35-2.05-4.24-4.4-4.23");
}

.cnc4zrbkq {
  stop-color: var(--svg-color--bba2c5, #BBA2C5);
  stop-opacity: 0;
}

.cr8gwobax {
  stop-color: var(--svg-color--cbb7d8, #CBB7D8);
}

.eatsizbuc {
  stop-color: var(--svg-color--ffc770, #FFC770);
}

.ecfxhclsg {
  stop-color: var(--svg-color--dad5dd, #DAD5DD);
  stop-opacity: 0;
}

.f9xkwoapo {
  stop-color: var(--svg-color--f27c46, #F27C46);
  stop-opacity: 0;
}

.fni_88bln {
  stop-color: var(--svg-color--c1b9c7, #C1B9C7);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g1-68ybmr {
  stop-color: var(--svg-color--d1c8dc, #D1C8DC);
  stop-opacity: 0;
}

.g8eva8vyf {
  stop-color: var(--svg-color--ec8023, #EC8023);
}

.ga4joklrv {
  stop-color: var(--svg-color--c6c3c7, #C6C3C7);
  stop-opacity: 0;
}

.gehzaab4q {
  stop-color: var(--svg-color--898591, #898591);
  stop-opacity: 0;
}

.gihuc0b-f {
  d: path("M9.578 7.14a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.gsi1nvbgo {
  stop-color: var(--svg-color--b6a6bb, #B6A6BB);
}

.gvgwa7ijg {
  d: path("M22.329 25a2.7 2.7 0 0 0-4.587.012a.35.35 0 0 1 .258.338v.71c0 .52.42.94.94.94h2.12c.52 0 .94-.42.94-.94v-.75a.31.31 0 0 1 .31-.31z");
}

.gzcz9plvc {
  stop-color: var(--svg-color--ffe395, #FFE395);
}

.h-9mxf4ip {
  stop-color: var(--svg-color--634e68, #634E68);
  stop-opacity: 0;
}

.h1t1vibrh {
  fill: var(--svg-color--e0dae4, #E0DAE4);
  d: path("M3.52 10.76A2.74 2.74 0 0 1 2 8.3C2 6.48 3.48 5 5.3 5h.9c.63 0 1.24-.26 1.65-.73c.65-.76 1.63-1.23 2.71-1.19c1.84.05 3.33 1.57 3.36 3.41A3.46 3.46 0 0 1 10.46 10H4v.46c0 .25-.26.41-.48.3");
}

.h2_c79j8v {
  stop-color: var(--svg-color--ffc770, #FFC770);
  stop-opacity: 0;
}

.h39-kzb5n {
  stop-color: var(--svg-color--f27c46, #F27C46);
}

.hze5bs0rc {
  stop-color: var(--svg-color--a292ac, #A292AC);
  stop-opacity: 0;
}

.ij45wmb6b {
  stop-color: var(--svg-color--8b8b92, #8B8B92);
}

.je5ihcbnd {
  stop-color: var(--svg-color--8e8e93, #8E8E93);
}

.jpyr-2r-q {
  stop-color: var(--svg-color--99729d, #99729D);
  stop-opacity: 0;
}

.kp85l4ben {
  stop-color: var(--svg-color--b4a3bb, #B4A3BB);
}

.l_n6ri8oc {
  stop-color: var(--svg-color--c6c3c7, #C6C3C7);
}

.l-3kk-jhn {
  stop-color: var(--svg-color--634e68, #634E68);
}

.m0p6scoik {
  stop-color: var(--svg-color--7e5e8c, #7E5E8C);
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mykl90e_w {
  stop-color: var(--svg-color--c2a9d1, #C2A9D1);
  stop-opacity: 0;
}

.n-c7wwb5q {
  d: path("M27.5 13a2.5 2.5 0 0 0-2.5 2.5V17h1.484L27 19.02c0 .72.41 1.38 1.05 1.7l.49.25c.21.11.46-.05.46-.28v-1.2c0-.32.07-.63.22-.92l.11-.23c.44-.88.67-1.85.67-2.84a2.5 2.5 0 0 0-2.5-2.5");
}

.n0mo5ylhv {
  stop-color: var(--svg-color--c6c3cf, #C6C3CF);
}

.n9i8a1bqy {
  stop-color: var(--svg-color--ff9339, #FF9339);
  stop-opacity: 0;
}

.nid9_0tuv {
  fill: var(--svg-color--ffc03f, #FFC03F);
  d: path("M2 8.3c0 1.05.59 2 1.52 2.46c.22.11.48-.05.48-.3a.46.46 0 0 1 .46-.46H6V5.7c0-.39-.31-.7-.7-.7C3.48 5 2 6.48 2 8.3");
}

.nw-wxtb6l {
  d: path("m13.625 9.063l-2.844 5.062h2.188");
}

.o16_3abrg {
  stop-color: var(--svg-color--9b93a1, #9B93A1);
}

.ogcd6k74i {
  stop-color: var(--svg-color--ccbbd1, #CCBBD1);
}

.oi1lpacrg {
  stop-color: var(--svg-color--c5aecd, #C5AECD);
  stop-opacity: 0;
}

.oskfltbrz {
  d: path("M17.99 29h-.7a.3.3 0 0 1-.3-.3V27h-2v1.7a.3.3 0 0 1-.3.3h-1.7c-.5 0-.916.37-.989.85c-.012.082.056.15.139.15h6.85c0-.55-.45-1-1-1");
}

.ox-6_8b4t {
  stop-color: var(--svg-color--898591, #898591);
}

.pqln2p5ve {
  stop-color: var(--svg-color--7e5e8c, #7E5E8C);
  stop-opacity: 0;
}

.px0djmbvk {
  stop-color: var(--svg-color--bdb8c6, #BDB8C6);
}

.pyli1tb4h {
  stop-color: var(--svg-color--bba2c5, #BBA2C5);
}

.q99c3li_e {
  stop-color: var(--svg-color--a07794, #A07794);
}

.q9umy0b_q {
  stop-color: var(--svg-color--dad5dd, #DAD5DD);
}

.qhtmvobwn {
  stop-color: var(--svg-color--b6a6bb, #B6A6BB);
  stop-opacity: 0;
}

.qtmmk-biq {
  stop-color: var(--svg-color--c5aecd, #C5AECD);
}

.ri9i1ztjv {
  stroke: var(--svg-color--ffc770, #FFC770);
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M20.453 29.313h1.635a.5.5 0 0 1 .405.207l.155.214");
}

.s5_1en1fk {
  stop-color: var(--svg-color--c1b9c7, #C1B9C7);
}

.sh1k17b4x {
  stop-color: var(--svg-color--ec8023, #EC8023);
  stop-opacity: 0;
}

.sr-f_tbjn {
  stroke: var(--svg-color--bdb8c6, #BDB8C6);
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.594 15.489c1.75-1.563 6.469-3.406 11.187.312");
}

.t2colpbsg {
  d: path("M2 8.3c0 1.05.59 2 1.52 2.46c.22.11.48-.05.48-.3a.46.46 0 0 1 .46-.46H6V5.7c0-.39-.31-.7-.7-.7C3.48 5 2 6.48 2 8.3");
}

.t53t9pbnf {
  stop-color: var(--svg-color--cdbddb, #CDBDDB);
}

.taj1jgbfl {
  d: path("M26.55 18.9a3.45 3.45 0 1 0 0-6.9a3.45 3.45 0 0 0 0 6.9");
}

.th_gchbom {
  stop-color: var(--svg-color--bcb5c7, #BCB5C7);
}

.tvsrpdltd {
  stop-color: var(--svg-color--e1dce4, #E1DCE4);
}

.tyu38-e5w {
  d: path("M20.77 20.63c-.16 0-.29-.14-.27-.31c.01-.06.04-.12.09-.17c.6-.58.95-1.41.9-2.32a2.98 2.98 0 0 0-2.8-2.82a3.006 3.006 0 0 0-3.2 2.91v1.46c0 2.35 1.9 4.25 4.25 4.25a2.99 2.99 0 0 0 2.95-2.48a.443.443 0 0 0-.44-.52z");
}

.u05lukb9u {
  stop-color: var(--svg-color--e4dbef, #E4DBEF);
}

.u0dgppboj {
  stop-color: var(--svg-color--b4a3bb, #B4A3BB);
  stop-opacity: 0;
}

.up-6wl8dn {
  stop-color: var(--svg-color--99729d, #99729D);
}

.ux9wxdawy {
  stop-color: var(--svg-color--d1c8dc, #D1C8DC);
}

.uzf94jp_m {
  stop-color: var(--svg-color--ffcb7f, #FFCB7F);
}

.v76lrjbcu {
  stop-color: var(--svg-color--c6c3cf, #C6C3CF);
  stop-opacity: 0;
}

.via_oubyr {
  stop-color: var(--svg-color--9b93a1, #9B93A1);
  stop-opacity: 0;
}

.vlbfw8bfy {
  stop-color: var(--svg-color--bcb5c7, #BCB5C7);
  stop-opacity: 0;
}

.vpg3ucb1n {
  stop-color: var(--svg-color--8b8b92, #8B8B92);
  stop-opacity: 0;
}

.vuad6pb7r {
  stop-color: var(--svg-color--1c1c1c, #1C1C1C);
}

.wwimjchyj {
  stop-color: var(--svg-color--a07794, #A07794);
  stop-opacity: 0;
}

.x6q59gjjw {
  stop-color: var(--svg-color--ffcb7f, #FFCB7F);
  stop-opacity: 0;
}

.x8mnt0d2r {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M16.844 29.453h2.11");
}

.xfk6amb8v {
  fill: var(--svg-color--ffb244, #FFB244);
  d: path("M22 29h-.7a.3.3 0 0 1-.3-.3V27h-2v1.7a.3.3 0 0 1-.3.3H17c-.5 0-.916.37-.989.85c-.012.082.056.15.139.15h6.7c.083 0 .151-.068.139-.15c-.073-.48-.49-.85-.989-.85");
}

.xrux4ni3c {
  fill: var(--svg-color--ffa739, #FFA739);
  d: path("M17.99 29h-.7a.3.3 0 0 1-.3-.3V27h-2v1.7a.3.3 0 0 1-.3.3h-1.7c-.5 0-.916.37-.989.85c-.012.082.056.15.139.15h6.85c0-.55-.45-1-1-1");
}

.y01kc3b8i {
  d: path("M22 29h-.7a.3.3 0 0 1-.3-.3V27h-2v1.7a.3.3 0 0 1-.3.3H17c-.5 0-.916.37-.989.85c-.012.082.056.15.139.15h6.7c.083 0 .151-.068.139-.15c-.073-.48-.49-.85-.989-.85");
}

.y6fg1wbjg {
  stop-color: var(--svg-color--c2a9d1, #C2A9D1);
}

.yvl4y2bse {
  d: path("M11.47 2a4.38 4.38 0 0 0-3.24 7.31h3.05v.07l-.63.12l-2.68 4.67A7.5 7.5 0 0 0 7 17.84C7 21.79 10.21 25 14.16 25h3.49a.35.35 0 0 1 .35.35v.71c0 .52.42.94.94.94h2.12c.52 0 .94-.42.94-.94v-.75a.31.31 0 0 1 .31-.31C24.9 25 27 22.9 27 20.31v-2.88c0-.99-.43-1.93-1.19-2.57c-2.12-1.8-4.82-2.97-7.81-2.97c-1.61 0-3.14.31-4.55.87c-.29.11-.55-.2-.4-.46l2.19-3.64c.43-.7.66-1.54.63-2.43c-.08-2.35-2.05-4.24-4.4-4.23");
}

.yzk018vul {
  stop-color: var(--svg-color--9b9c9f, #9B9C9F);
}

.z_1mb4bjp {
  stop-color: var(--svg-color--bdb8c6, #BDB8C6);
  stop-opacity: 0;
}

.z2o935btm {
  stop-color: var(--svg-color--9d9ca4, #9D9CA4);
  stop-opacity: 0;
}

.zlhreg8au {
  stop-color: var(--svg-color--c0baca, #C0BACA);
}

.znh-hdc4k {
  d: path("M3.52 10.76A2.74 2.74 0 0 1 2 8.3C2 6.48 3.48 5 5.3 5h.9c.63 0 1.24-.26 1.65-.73c.65-.76 1.63-1.23 2.71-1.19c1.84.05 3.33 1.57 3.36 3.41A3.46 3.46 0 0 1 10.46 10H4v.46c0 .25-.26.41-.48.3");
}

.zqw2376vi {
  fill: var(--svg-color--a682ad, #A682AD);
  d: path("M17.06 27h-2.12c-.52 0-.94-.42-.94-.94V23h4v3.06c0 .52-.42.94-.94.94");
}

</style>
