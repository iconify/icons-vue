<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect stroke="url(#iiUee4d)" class="hel0l0yos"/><g filter="url(#iqCxdNc)"><rect stroke="url(#id9azOb)" class="voubcyb0r"/></g><path class="x47dg6b2x"/><g filter="url(#ibtmMGq)"><path fill="url(#iF3y6FS)" class="fhs9rccle"/><path fill="url(#ia5EZyc)" class="fhs9rccle"/><path fill="url(#iG2ziVb)" class="fhs9rccle"/></g><g filter="url(#il6LBTb)"><path stroke="url(#iSPsbPc)" class="f5ig9groa"/></g><g filter="url(#iNJWOYb)" class="atjk8mbde"><path stroke="url(#i0dytzd)" class="a5p8tdbvo"/><path stroke="url(#i1x864b)" class="a5p8tdbvo"/></g><g filter="url(#iEwn68b)" class="dwos04rta"><path stroke="url(#ilHFQfd)" class="psx6hlupy"/><path stroke="url(#icGS52c)" class="psx6hlupy"/></g><g filter="url(#iS9xo5w)"><rect class="w7r-ai4nm"/><rect fill="url(#iKIcGsc)" class="sylngrzqj"/></g><g filter="url(#iSAXeic)"><path fill="url(#id7e8cw)" class="ta4mgjboh"/><path fill="url(#ihaRFNd)" class="ta4mgjboh"/><path fill="url(#i6cBlTL)" class="ta4mgjboh"/></g><path fill="url(#i1IsW3d)" class="s54n8e9wd"/><g filter="url(#i9ouDZd)"><path fill="url(#i2HY0UR)" clip-rule="evenodd" class="kvi365bad"/></g><defs><linearGradient id="id9azOb" x1="19.953" x2="14.609" y1="5.281" y2="3.406" gradientUnits="userSpaceOnUse"><stop class="ky6hycc-n"/><stop offset="1" class="naxihcihm"/></linearGradient><linearGradient id="ia5EZyc" x1="26.063" x2="15.438" y1="30.563" y2="23.188" gradientUnits="userSpaceOnUse"><stop class="oxp9tf80q"/><stop offset="1" class="m_k88e8vl"/></linearGradient><linearGradient id="iG2ziVb" x1="5.375" x2="11.375" y1="29.563" y2="21.188" gradientUnits="userSpaceOnUse"><stop offset=".035" class="hg6anmb7n"/><stop offset="1" class="nmj0g16xz"/></linearGradient><linearGradient id="iSPsbPc" x1="24.016" x2="12.008" y1="10.288" y2="10.288" gradientUnits="userSpaceOnUse"><stop class="memhf97za"/><stop offset="1" class="eq2vkccmb"/></linearGradient><linearGradient id="i0dytzd" x1="7.082" x2="15.313" y1="11.469" y2="11.469" gradientUnits="userSpaceOnUse"><stop class="x3turyh5c"/><stop offset="1" class="zhyd8eavz"/></linearGradient><linearGradient id="i1x864b" x1="24.418" x2="18.875" y1="11.813" y2="6.797" gradientUnits="userSpaceOnUse"><stop class="hw0vm1bfh"/><stop offset="1" class="trj_5xbxj"/></linearGradient><linearGradient id="ilHFQfd" x1="25.344" x2="16.938" y1="11.625" y2="5.688" gradientUnits="userSpaceOnUse"><stop class="bfna0bhkq"/><stop offset="1" class="tj0gg2bhw"/></linearGradient><linearGradient id="icGS52c" x1="7.5" x2="11.188" y1="11.906" y2="8.219" gradientUnits="userSpaceOnUse"><stop class="jciknrbpe"/><stop offset="1" class="g2qu-pb3k"/></linearGradient><linearGradient id="ihaRFNd" x1="16.688" x2="16.688" y1="30.438" y2="26.563" gradientUnits="userSpaceOnUse"><stop class="kk2zq88sj"/><stop offset="1" class="hc6aknb8i"/></linearGradient><filter id="iqCxdNc" width="9.637" height="13.825" x="11.338" y="2.15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17138" stdDeviation=".2"/></filter><filter id="ibtmMGq" width="22.25" height="25.102" x="4.75" y="5.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.329412 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17138"/></filter><filter id="il6LBTb" width="18.934" height="7.182" x="6.082" y="5.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17138" stdDeviation=".25"/></filter><filter id="iNJWOYb" width="18.336" height="6.391" x="6.582" y="6.197" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.380392 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17138"/></filter><filter id="iEwn68b" width="18.386" height="6.341" x="6.807" y="6.272" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17138" stdDeviation=".2"/></filter><filter id="iS9xo5w" width="7.953" height="4.978" x="11.697" y="8.209" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.176471 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_17138"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_17138" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.521569 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_17138"/></filter><filter id="iSAXeic" width="17.606" height="13.008" x="7.047" y="16.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894969 0 0 0 0 0.370192 0 0 0 0 0.466334 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17138"/></filter><filter id="i9ouDZd" width="2.238" height="3.364" x="6.348" y="22.768" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.694118 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17138"/></filter><radialGradient id="iiUee4d" cx="0" cy="0" r="1" gradientTransform="rotate(141.554 9.155 4.805)scale(5.22698 8.81171)" gradientUnits="userSpaceOnUse"><stop class="oqv-d7zwi"/><stop offset="1" class="nyhvbftvv"/></radialGradient><radialGradient id="iF3y6FS" cx="0" cy="0" r="1" gradientTransform="matrix(-5.75002 13.93747 -13.108 -5.40781 19.688 10.5)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="cc8uz77ix"/><stop offset="1" class="v0od0abbq"/></radialGradient><radialGradient id="iKIcGsc" cx="0" cy="0" r="1" gradientTransform="matrix(5.09375 0 0 4.62022 13.813 10.598)" gradientUnits="userSpaceOnUse"><stop offset=".791" class="k-w4sbvlf"/><stop offset="1" class="ayqsnux1l"/></radialGradient><radialGradient id="id7e8cw" cx="0" cy="0" r="1" gradientTransform="matrix(-6.8125 7.62499 -7.84632 -7.01025 21.875 20.563)" gradientUnits="userSpaceOnUse"><stop class="ulpywj_5w"/><stop offset="1" class="qkh-begvk"/></radialGradient><radialGradient id="i6cBlTL" cx="0" cy="0" r="1" gradientTransform="matrix(14.70305 4.0626 -4.1608 15.05844 9.75 24.438)" gradientUnits="userSpaceOnUse"><stop offset=".904" class="ycpscubfx"/><stop offset="1" class="t_g0_dbtm"/></radialGradient><radialGradient id="i1IsW3d" cx="0" cy="0" r="1" gradientTransform="rotate(127.129 6.447 14.118)scale(9.68135 18.4675)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="usw56ebyd"/><stop offset="1" class="b3v605pxp"/></radialGradient><radialGradient id="i2HY0UR" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.64062 1.0426 0 7.517 25.156)" gradientUnits="userSpaceOnUse"><stop class="q222xpb8m"/><stop offset="1" class="jxnftcbhw"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:backpack" /></template>
<style>
.a5p8tdbvo {
  d: path("M7.082 12.088a9.74 9.74 0 0 1 8.668-5.291a9.74 9.74 0 0 1 8.668 5.29");
}

.atjk8mbde {
  stroke-linecap: round;
}

.ayqsnux1l {
  stop-color: var(--svg-color--ffeb6d, #FFEB6D);
}

.b3v605pxp {
  stop-color: var(--svg-color--aa2743, #AA2743);
}

.bfna0bhkq {
  stop-color: var(--svg-color--ffef6f, #FFEF6F);
}

.cc8uz77ix {
  stop-color: var(--svg-color--ff5aac, #FF5AAC);
}

.dwos04rta {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
}

.eq2vkccmb {
  stop-color: var(--svg-color--da2d56, #DA2D56);
}

.f5ig9groa {
  stroke-linecap: round;
  d: path("M7.082 12.088a9.51 9.51 0 0 1 8.467-5.182a9.51 9.51 0 0 1 8.467 5.182");
}

.fhs9rccle {
  d: path("M4.75 16.094c0-6.075 4.925-11 11-11s11 4.925 11 11v9.851a4 4 0 0 1-4 4h-14a4 4 0 0 1-4-4z");
}

.ft5dv1b6b {
  fill: none;
}

.g2qu-pb3k {
  stop-color: var(--svg-color--f78843, #F78843);
  stop-opacity: 0;
}

.hc6aknb8i {
  stop-color: var(--svg-color--e41863, #E41863);
  stop-opacity: 0;
}

.hel0l0yos {
  width: 8.188px;
  height: 12.375px;
  x: 11.734px;
  y: 2.875px;
  stroke-width: var(--svg-stroke-width--1-65px, 1.65px);
  rx: 4.094px;
}

.hg6anmb7n {
  stop-color: var(--svg-color--d64456, #D64456);
}

.hw0vm1bfh {
  stop-color: var(--svg-color--ffc74b, #FFC74B);
}

.jciknrbpe {
  stop-color: var(--svg-color--f78843, #F78843);
}

.jxnftcbhw {
  stop-color: var(--svg-color--ffaf4d, #FFAF4D);
}

.k-w4sbvlf {
  stop-color: var(--svg-color--ffeb6d, #FFEB6D);
  stop-opacity: 0;
}

.kk2zq88sj {
  stop-color: var(--svg-color--e41863, #E41863);
}

.kvi365bad {
  fill-rule: evenodd;
  d: path("M7.523 22.768a.79.79 0 0 0-.792.732l-.276 1.89a.653.653 0 0 0 .652.743h.82c.4 0 .708-.349.653-.74l-.264-1.865c-.036-.426-.362-.76-.793-.76m-.015 1.236a.453.453 0 1 0 0-.906a.453.453 0 0 0 0 .906");
}

.ky6hycc-n {
  stop-color: var(--svg-color--d85773, #D85773);
}

.m_k88e8vl {
  stop-color: var(--svg-color--f63659, #F63659);
  stop-opacity: 0;
}

.memhf97za {
  stop-color: var(--svg-color--ff2274, #FF2274);
}

.naxihcihm {
  stop-color: var(--svg-color--bd385c, #BD385C);
}

.nmj0g16xz {
  stop-color: var(--svg-color--d64456, #D64456);
  stop-opacity: 0;
}

.nyhvbftvv {
  stop-color: var(--svg-color--af3349, #AF3349);
}

.oqv-d7zwi {
  stop-color: var(--svg-color--ce4767, #CE4767);
}

.oxp9tf80q {
  stop-color: var(--svg-color--f63659, #F63659);
}

.psx6hlupy {
  d: path("M7.332 12.088A9.74 9.74 0 0 1 16 6.797a9.74 9.74 0 0 1 8.668 5.29");
}

.q222xpb8m {
  stop-color: var(--svg-color--ffb54e, #FFB54E);
}

.qkh-begvk {
  stop-color: var(--svg-color--f02779, #F02779);
}

.s54n8e9wd {
  d: path("M7.057 25.219a8.703 8.703 0 0 1 17.386 0q.01-.21.01-.422a8.703 8.703 0 1 0-17.396.422");
}

.sylngrzqj {
  width: 5.953px;
  height: 2.978px;
  x: 12.797px;
  y: 9.109px;
  rx: 1.25px;
}

.t_g0_dbtm {
  stop-color: var(--svg-color--f55178, #F55178);
}

.ta4mgjboh {
  d: path("M21.573 29.945c1.078 0 2.113-.566 2.448-1.59a8.703 8.703 0 1 0-16.543 0c.336 1.024 1.372 1.59 2.45 1.59z");
}

.tj0gg2bhw {
  stop-color: var(--svg-color--ffef6f, #FFEF6F);
  stop-opacity: 0;
}

.trj_5xbxj {
  stop-color: var(--svg-color--ffc24c, #FFC24C);
  stop-opacity: 0;
}

.ulpywj_5w {
  stop-color: var(--svg-color--ff56a6, #FF56A6);
}

.usw56ebyd {
  stop-color: var(--svg-color--cb184d, #CB184D);
}

.v0od0abbq {
  stop-color: var(--svg-color--e02e7a, #E02E7A);
}

.voubcyb0r {
  width: 8.188px;
  height: 12.375px;
  x: 12.063px;
  y: 2.875px;
  stroke-width: var(--svg-stroke-width--0-65px, 0.65px);
  rx: 4.094px;
}

.w7r-ai4nm {
  width: 5.953px;
  height: 2.978px;
  x: 12.797px;
  y: 9.109px;
  fill: var(--svg-color--ffc442, #FFC442);
  rx: 1.25px;
}

.x3turyh5c {
  stop-color: var(--svg-color--e98832, #E98832);
}

.x47dg6b2x {
  fill: var(--svg-color--c4c4c4, #C4C4C4);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M4.75 16.094c0-6.075 4.925-11 11-11s11 4.925 11 11v9.851a4 4 0 0 1-4 4h-14a4 4 0 0 1-4-4z");
}

.ycpscubfx {
  stop-color: var(--svg-color--f55178, #F55178);
  stop-opacity: 0;
}

.zhyd8eavz {
  stop-color: var(--svg-color--ffc349, #FFC349);
}

</style>
