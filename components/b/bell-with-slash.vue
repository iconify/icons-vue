<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#iOBboJe)" class="q9ty2i-3o"/><circle fill="url(#i2bL6iJ)" class="q9ty2i-3o"/><circle fill="url(#iP3hdLb)" class="q9ty2i-3o"/><g filter="url(#iGjcUmb)"><rect fill="url(#imX4Ofb)" class="ou6uhb65l"/></g><g filter="url(#in7HGEd)"><path fill="url(#iQPOSKr)" class="vuttaxbiw"/></g><path fill="url(#iBzJZ3c)" class="vuttaxbiw"/><path fill="url(#icqKRPe)" class="vuttaxbiw"/><g filter="url(#ibkvEEe)"><path fill="url(#i8wdwfe)" class="x_qtt1zsh"/></g><g filter="url(#ifowlUQ)"><path fill="url(#iYXDc9F)" class="v5wmh_bni"/></g><g filter="url(#izme9Lb)"><path fill="url(#iSUzSUc)" class="ze7076bgj"/></g><defs><linearGradient id="i2bL6iJ" x1="15.253" x2="15.503" y1="26.764" y2="28.545" gradientUnits="userSpaceOnUse"><stop offset=".186" class="jag0fvlrr"/><stop offset="1" class="mo_bi6bip"/></linearGradient><linearGradient id="iQPOSKr" x1="18.46" x2="4.938" y1="25.701" y2="25.701" gradientUnits="userSpaceOnUse"><stop class="ok-kfhbvl"/><stop offset="1" class="lrxof5grr"/></linearGradient><linearGradient id="iBzJZ3c" x1="18.097" x2="18.097" y1="27.795" y2="24.795" gradientUnits="userSpaceOnUse"><stop class="ysc8j8jes"/><stop offset=".302" class="er6dmpbfb"/></linearGradient><linearGradient id="i8wdwfe" x1="6.221" x2="26.284" y1="23.045" y2="23.045" gradientUnits="userSpaceOnUse"><stop offset=".277" class="bdkdieb9c"/><stop offset="1" class="hfzg5gbqa"/></linearGradient><linearGradient id="iYXDc9F" x1="25.166" x2="15.534" y1="18.18" y2="18.18" gradientUnits="userSpaceOnUse"><stop offset=".118" class="b5thbpbci"/><stop offset="1" class="fb38qrwvp"/></linearGradient><linearGradient id="iSUzSUc" x1="8.372" x2="28.55" y1="8.411" y2="28.108" gradientUnits="userSpaceOnUse"><stop class="ebhz7ue_y"/><stop offset="1" class="lmjh-8bvl"/></linearGradient><filter id="iGjcUmb" width="2.608" height="4.361" x="14.789" y="1.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.564706 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18000"/></filter><filter id="in7HGEd" width="30.921" height="23.688" x="-.968" y="3.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-4"/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.905882 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18000"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.996078 0 0 0 0 0.866667 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_18000" result="effect2_innerShadow_18_18000"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.572549 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_18000" result="effect3_innerShadow_18_18000"/></filter><filter id="ibkvEEe" width="25" height="6.125" x="3.909" y="18.92" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18000" stdDeviation="1"/></filter><filter id="ifowlUQ" width="11.5" height="18.25" x="14.784" y="4.67" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18000" stdDeviation="1"/></filter><filter id="izme9Lb" width="27.756" height="27.756" x="2.147" y="1.779" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.14902 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18000"/></filter><radialGradient id="iOBboJe" cx="0" cy="0" r="1" gradientTransform="rotate(-126.512 16.226 10.112)scale(2.95496 4.08094)" gradientUnits="userSpaceOnUse"><stop class="wl92h9oon"/><stop offset="1" class="zk76so6po"/></radialGradient><radialGradient id="iP3hdLb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.875 2.875 -4.74402 -4.74402 16.88 26.328)" gradientUnits="userSpaceOnUse"><stop offset=".441" class="k3-xt3bvs"/><stop offset="1" class="fn3rhsbaf"/></radialGradient><radialGradient id="imX4Ofb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.18066 1.3125 0 16.784 3.848)" gradientUnits="userSpaceOnUse"><stop class="e0lykt_ig"/><stop offset="1" class="a5u00eqrt"/></radialGradient><radialGradient id="icqKRPe" cx="0" cy="0" r="1" gradientTransform="matrix(-19.00185 12.74995 -12.23105 -18.22851 22.034 14.233)" gradientUnits="userSpaceOnUse"><stop offset=".67" class="hdtgov6cy"/><stop offset=".977" class="r0oouklgp"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:bell-with-slash" /></template>
<style>
.a5u00eqrt {
  stop-color: var(--svg-color--f7a630, #F7A630);
}

.b5thbpbci {
  stop-color: var(--svg-color--ffef6d, #FFEF6D);
}

.bdkdieb9c {
  stop-color: var(--svg-color--f5a43c, #F5A43C);
}

.e0lykt_ig {
  stop-color: var(--svg-color--ffe957, #FFE957);
}

.ebhz7ue_y {
  stop-color: var(--svg-color--fe3c57, #FE3C57);
}

.er6dmpbfb {
  stop-color: var(--svg-color--fca162, #FCA162);
  stop-opacity: 0;
}

.fb38qrwvp {
  stop-color: var(--svg-color--ffef6d, #FFEF6D);
  stop-opacity: 0;
}

.fn3rhsbaf {
  stop-color: var(--svg-color--c27068, #C27068);
}

.ft5dv1b6b {
  fill: none;
}

.hdtgov6cy {
  stop-color: var(--svg-color--e69136, #E69136);
  stop-opacity: 0;
}

.hfzg5gbqa {
  stop-color: var(--svg-color--ffe154, #FFE154);
}

.jag0fvlrr {
  stop-color: var(--svg-color--e57356, #E57356);
}

.k3-xt3bvs {
  stop-color: var(--svg-color--ea8059, #EA8059);
  stop-opacity: 0;
}

.lmjh-8bvl {
  stop-color: var(--svg-color--ff37b8, #FF37B8);
}

.lrxof5grr {
  stop-color: var(--svg-color--e28c37, #E28C37);
}

.mo_bi6bip {
  stop-color: var(--svg-color--e57356, #E57356);
  stop-opacity: 0;
}

.ok-kfhbvl {
  stop-color: var(--svg-color--fcb949, #FCB949);
}

.ou6uhb65l {
  width: 2.408px;
  height: 4.361px;
  x: 14.789px;
  y: 1.668px;
  rx: 1.204px;
}

.q9ty2i-3o {
  cx: 15.995px;
  cy: 25.874px;
  r: 3.661px;
}

.r0oouklgp {
  stop-color: var(--svg-color--cf7d44, #CF7D44);
}

.v5wmh_bni {
  d: path("M16.784 8.934a2.264 2.264 0 0 1 4.464-.534l3.036 12.52h-7.5z");
}

.vuttaxbiw {
  d: path("M7.971 10.281a8 8 0 0 1 7.765-6.433h.513a8 8 0 0 1 7.766 6.433l1.86 9.317c.134.67.438 1.294.881 1.814l1.24 1.451a4 4 0 0 1 .957 2.597v1.326a.75.75 0 0 1-.75.75H3.783a.75.75 0 0 1-.75-.75V25.46a4 4 0 0 1 .957-2.597l1.24-1.451a4 4 0 0 0 .88-1.814z");
}

.wl92h9oon {
  stop-color: var(--svg-color--ffc26d, #FFC26D);
}

.x_qtt1zsh {
  d: path("M7.471 20.92L5.91 23.045h21l-1.69-2.125z");
}

.ysc8j8jes {
  stop-color: var(--svg-color--d7737d, #D7737D);
}

.ze7076bgj {
  d: path("M2.555 2.237a1.393 1.393 0 0 1 1.97 0l24.92 24.92a1.393 1.393 0 0 1-1.97 1.97L2.555 4.207a1.393 1.393 0 0 1 0-1.97");
}

.zk76so6po {
  stop-color: var(--svg-color--f68d61, #F68D61);
}

</style>
