<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#idx1S1c)" class="fdcu_iflm"/><path fill="url(#iBWpnBd)" class="fdcu_iflm"/><path fill="url(#ie0t8ue)" class="fdcu_iflm"/><path fill="url(#iXCpUeX)" class="fdcu_iflm"/><path fill="url(#ijp7Ind)" class="fdcu_iflm"/><path fill="url(#iqXb8pC)" class="fdcu_iflm"/><g filter="url(#iep31De)"><path class="yfzrotb1l"/><path fill="url(#i70L99M)" class="ojqcgkxhf"/><path fill="url(#iMV02lc)" class="ojqcgkxhf"/><path fill="url(#ihqM1kc)" class="ojqcgkxhf"/></g><g filter="url(#iqtk1Ac)"><rect class="ec9t1rcni"/><rect fill="url(#iHSIaMc)" class="y2fz7gbgc"/><rect fill="url(#ivEYHGd)" class="y2fz7gbgc"/></g><g filter="url(#ipQ2FUc)"><rect class="m7fe7euxw"/><rect fill="url(#iYvuCxp)" class="w6bu7upae"/><rect fill="url(#iVhn7AB)" class="w6bu7upae"/></g><g filter="url(#irKXSfb)"><path fill="url(#inA33md)" class="ospdr8b9d"/><path fill="url(#iMgg0ke)" class="ospdr8b9d"/></g><g filter="url(#iLBn6nb)"><path stroke="url(#i9T44Sc)" class="fdkfevo0e"/></g><g filter="url(#iuUmbsb)"><path stroke="url(#i4yt0od)" class="yn5nv0sht"/></g><defs><linearGradient id="ie0t8ue" x1="1.781" x2="10.031" y1="25.5" y2="25.5" gradientUnits="userSpaceOnUse"><stop class="s3r5qsbwk"/><stop offset="1" class="hwz2uwbxm"/></linearGradient><linearGradient id="iXCpUeX" x1="16" x2="16" y1="8.813" y2="12.375" gradientUnits="userSpaceOnUse"><stop class="ltlxfxt2n"/><stop offset="1" class="m1bu-4bkx"/></linearGradient><linearGradient id="iqXb8pC" x1="16" x2="16" y1="8.5" y2="9.438" gradientUnits="userSpaceOnUse"><stop class="fj6vs643s"/><stop offset="1" class="fsewj8bfo"/></linearGradient><linearGradient id="i70L99M" x1="2.469" x2="9.844" y1="29.313" y2="29.313" gradientUnits="userSpaceOnUse"><stop offset=".432" class="wqeet8brd"/><stop offset="1" class="b6x03ebvm"/></linearGradient><linearGradient id="iMV02lc" x1="29.875" x2="21.781" y1="28.688" y2="28.813" gradientUnits="userSpaceOnUse"><stop offset=".5" class="nl8cndhji"/><stop offset="1" class="gqgsqlb8b"/></linearGradient><linearGradient id="ihqM1kc" x1="29.875" x2="26.781" y1="28.188" y2="28.188" gradientUnits="userSpaceOnUse"><stop class="ree4beb7o"/><stop offset="1" class="ailv20byd"/></linearGradient><linearGradient id="inA33md" x1="9.719" x2="1.031" y1="9.375" y2="12.563" gradientUnits="userSpaceOnUse"><stop class="uslbdol9i"/><stop offset="1" class="u0f1z7byk"/></linearGradient><linearGradient id="i9T44Sc" x1="16.672" x2="20.316" y1="12.453" y2="12.453" gradientUnits="userSpaceOnUse"><stop class="fh_d7tfdx"/><stop offset="1" class="ex-x7xb_o"/></linearGradient><linearGradient id="i4yt0od" x1="16.559" x2="20.297" y1="15.219" y2="15.219" gradientUnits="userSpaceOnUse"><stop class="fh_d7tfdx"/><stop offset="1" class="ex-x7xb_o"/></linearGradient><radialGradient id="idx1S1c" cx="0" cy="0" r="1" gradientTransform="rotate(136.019 7.174 11.802)scale(12.4205 16.2342)" gradientUnits="userSpaceOnUse"><stop class="v6oglab2u"/><stop offset="1" class="exgcikb8h"/></radialGradient><radialGradient id="iBWpnBd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.6875 13 0 25.844 26.125)" gradientUnits="userSpaceOnUse"><stop class="pwthmn95t"/><stop offset="1" class="mgmr4wj_u"/></radialGradient><radialGradient id="ijp7Ind" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.125 -4.96875 0 16.375 10.281)" gradientUnits="userSpaceOnUse"><stop class="h6ybdtb1b"/><stop offset="1" class="b1hl1zbxi"/></radialGradient><radialGradient id="iHSIaMc" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 0 0 .75 16.453 13)" gradientUnits="userSpaceOnUse"><stop offset=".153" class="y1v53ubgk"/><stop offset="1" class="z_0tacb6y"/></radialGradient><radialGradient id="ivEYHGd" cx="0" cy="0" r="1" gradientTransform="rotate(153.204 8.412 8.46)scale(1.73297 4.83352)" gradientUnits="userSpaceOnUse"><stop class="rn9lkub7i"/><stop offset="1" class="zaupfx23d"/></radialGradient><radialGradient id="iYvuCxp" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 0 0 .75 16.453 15.727)" gradientUnits="userSpaceOnUse"><stop offset=".153" class="y1v53ubgk"/><stop offset="1" class="z_0tacb6y"/></radialGradient><radialGradient id="iVhn7AB" cx="0" cy="0" r="1" gradientTransform="rotate(153.204 8.087 9.823)scale(1.73297 4.83352)" gradientUnits="userSpaceOnUse"><stop class="rn9lkub7i"/><stop offset="1" class="zaupfx23d"/></radialGradient><radialGradient id="iMgg0ke" cx="0" cy="0" r="1" gradientTransform="matrix(-2.53126 -2.20311 4.12909 -4.74412 10.25 13.438)" gradientUnits="userSpaceOnUse"><stop class="bsah7jwro"/><stop offset="1" class="m9suppbgb"/></radialGradient><filter id="iep31De" width="27.75" height="4.672" x="2.125" y="25.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.211765 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17251"/></filter><filter id="iqtk1Ac" width="4.017" height="1.547" x="15.945" y="11.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.337255 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17251"/></filter><filter id="ipQ2FUc" width="4.017" height="1.547" x="15.945" y="14.453" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.337255 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17251"/></filter><filter id="irKXSfb" width="9.106" height="5.244" x="2.025" y="8.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.580392 0 0 0 0 0.286275 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17251"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.564706 0 0 0 0 0.462745 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_17251" result="effect2_innerShadow_18_17251"/></filter><filter id="iLBn6nb" width="3.478" height=".9" x="16.222" y="12.003" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17251" stdDeviation=".15"/></filter><filter id="iuUmbsb" width="3.544" height=".9" x="16.109" y="14.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17251" stdDeviation=".15"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hiking-boot" /></template>
<style>
.ailv20byd {
  stop-color: var(--svg-color--875b59, #875B59);
  stop-opacity: 0;
}

.b1hl1zbxi {
  stop-color: var(--svg-color--ffdc58, #FFDC58);
  stop-opacity: 0;
}

.b6x03ebvm {
  stop-color: var(--svg-color--5f383e, #5F383E);
  stop-opacity: 0;
}

.bsah7jwro {
  stop-color: var(--svg-color--9f5b6b, #9F5B6B);
}

.ec9t1rcni {
  width: 3.617px;
  height: 1.297px;
  x: 15.945px;
  y: 11.977px;
  fill: var(--svg-color--a26262, #A26262);
  rx: 0.648px;
}

.ex-x7xb_o {
  stop-color: var(--svg-color--bb8a86, #BB8A86);
  stop-opacity: 0;
}

.exgcikb8h {
  stop-color: var(--svg-color--ffa25d, #FFA25D);
}

.fdcu_iflm {
  d: path("M4.375 8.813a2.25 2.25 0 0 0-2.25 2.25V25.5h27.75c-.422-4.16-4.186-5.342-7.4-6.315l-.35-.107c-1.948-.593-2.907-2.524-3.124-3.77v-4.245a2.25 2.25 0 0 0-2.25-2.25z");
}

.fdkfevo0e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M16.672 12.453h2.578");
}

.fh_d7tfdx {
  stop-color: var(--svg-color--bb8a86, #BB8A86);
}

.fj6vs643s {
  stop-color: var(--svg-color--ddc76c, #DDC76C);
}

.fsewj8bfo {
  stop-color: var(--svg-color--ddc76c, #DDC76C);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gqgsqlb8b {
  stop-color: var(--svg-color--916366, #916366);
  stop-opacity: 0;
}

.h6ybdtb1b {
  stop-color: var(--svg-color--ffef7a, #FFEF7A);
}

.hwz2uwbxm {
  stop-color: var(--svg-color--ee944a, #EE944A);
  stop-opacity: 0;
}

.ltlxfxt2n {
  stop-color: var(--svg-color--ffe05b, #FFE05B);
}

.m1bu-4bkx {
  stop-color: var(--svg-color--ffe05b, #FFE05B);
  stop-opacity: 0;
}

.m7fe7euxw {
  width: 3.617px;
  height: 1.297px;
  x: 15.945px;
  y: 14.703px;
  fill: var(--svg-color--a26262, #A26262);
  rx: 0.648px;
}

.m9suppbgb {
  stop-color: var(--svg-color--9f5b6b, #9F5B6B);
  stop-opacity: 0;
}

.mgmr4wj_u {
  stop-color: var(--svg-color--ffce70, #FFCE70);
  stop-opacity: 0;
}

.nl8cndhji {
  stop-color: var(--svg-color--916366, #916366);
}

.ojqcgkxhf {
  d: path("M2.125 25.5h27.75v2.531c0 1.044-.878 1.89-1.96 1.89c-.746 0-1.394-.4-1.726-.99a.4.4 0 0 0-.338-.212h-.764a.4.4 0 0 0-.339.212c-.331.59-.98.99-1.725.99s-1.393-.4-1.725-.99a.4.4 0 0 0-.338-.212h-.608a.4.4 0 0 0-.338.212c-.332.59-.98.99-1.725.99s-1.393-.4-1.725-.99a.4.4 0 0 0-.338-.212h-.608a.4.4 0 0 0-.338.212c-.332.59-.98.99-1.725.99s-1.393-.4-1.725-.99a.4.4 0 0 0-.338-.212h-.609a.4.4 0 0 0-.338.212c-.332.59-.98.99-1.725.99s-1.393-.4-1.725-.99a.4.4 0 0 0-.338-.212H6.15a.4.4 0 0 0-.338.212c-.332.59-.98.99-1.725.99c-1.083 0-1.961-.846-1.961-1.89z");
}

.ospdr8b9d {
  d: path("M11.031 8.813v2.843a2 2 0 0 1-2 2H2.125v-2.594a2.25 2.25 0 0 1 2.25-2.25z");
}

.pwthmn95t {
  stop-color: var(--svg-color--ffce70, #FFCE70);
}

.ree4beb7o {
  stop-color: var(--svg-color--875b59, #875B59);
}

.rn9lkub7i {
  stop-color: var(--svg-color--b28f87, #B28F87);
}

.s3r5qsbwk {
  stop-color: var(--svg-color--b67f4a, #B67F4A);
}

.u0f1z7byk {
  stop-color: var(--svg-color--714c4c, #714C4C);
}

.uslbdol9i {
  stop-color: var(--svg-color--985a58, #985A58);
}

.v6oglab2u {
  stop-color: var(--svg-color--ffe06f, #FFE06F);
}

.w6bu7upae {
  width: 3.617px;
  height: 1.297px;
  x: 15.945px;
  y: 14.703px;
  rx: 0.648px;
}

.wqeet8brd {
  stop-color: var(--svg-color--5f383e, #5F383E);
}

.y1v53ubgk {
  stop-color: var(--svg-color--a75476, #A75476);
}

.y2fz7gbgc {
  width: 3.617px;
  height: 1.297px;
  x: 15.945px;
  y: 11.977px;
  rx: 0.648px;
}

.yfzrotb1l {
  fill: var(--svg-color--834763, #834763);
  d: path("M2.125 25.5h27.75v2.531c0 1.044-.878 1.89-1.96 1.89c-.746 0-1.394-.4-1.726-.99a.4.4 0 0 0-.338-.212h-.764a.4.4 0 0 0-.339.212c-.331.59-.98.99-1.725.99s-1.393-.4-1.725-.99a.4.4 0 0 0-.338-.212h-.608a.4.4 0 0 0-.338.212c-.332.59-.98.99-1.725.99s-1.393-.4-1.725-.99a.4.4 0 0 0-.338-.212h-.608a.4.4 0 0 0-.338.212c-.332.59-.98.99-1.725.99s-1.393-.4-1.725-.99a.4.4 0 0 0-.338-.212h-.609a.4.4 0 0 0-.338.212c-.332.59-.98.99-1.725.99s-1.393-.4-1.725-.99a.4.4 0 0 0-.338-.212H6.15a.4.4 0 0 0-.338.212c-.332.59-.98.99-1.725.99c-1.083 0-1.961-.846-1.961-1.89z");
}

.yn5nv0sht {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M16.559 15.219h2.644");
}

.z_0tacb6y {
  stop-color: var(--svg-color--a75476, #A75476);
  stop-opacity: 0;
}

.zaupfx23d {
  stop-color: var(--svg-color--a56666, #A56666);
  stop-opacity: 0;
}

</style>
