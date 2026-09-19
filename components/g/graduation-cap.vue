<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iRWbNRc)"><path fill="url(#ie7Fpsb)" class="chdi8kbgd"/></g><g filter="url(#ipZO8Ic)"><path fill="url(#ilwTGwc)" class="qyq_t6hnx"/></g><g filter="url(#iF1DVrd)"><path stroke="url(#ielAled)" class="vta_up4os"/></g><g filter="url(#iUp2Tbe)"><path fill="url(#iMrIIdc)" class="z69tstf1u"/></g><g filter="url(#iuFZmNN)"><path fill="url(#ivOxq7b)" class="b_iwr5rca"/></g><g filter="url(#iOgJVQb)"><path fill="url(#iZos7gb)" clip-rule="evenodd" class="noqswdaov"/></g><path fill="url(#inATgVd)" clip-rule="evenodd" class="noqswdaov"/><path fill="url(#irVNykw)" clip-rule="evenodd" class="noqswdaov"/><path fill="url(#iSkCfGb)" clip-rule="evenodd" class="noqswdaov"/><path fill="url(#iQXkdXb)" class="dvrm_kb6l"/><path fill="url(#iCMluse)" class="dvrm_kb6l"/><path fill="url(#i53Ii6b)" class="dvrm_kb6l"/><path class="x_ki2cbos"/><path fill="url(#iZwyZyd)" class="tb5su8b4w"/><path fill="url(#i0hs1zc)" class="tb5su8b4w"/><path fill="url(#iFR9NZb)" class="tb5su8b4w"/><defs><linearGradient id="ie7Fpsb" x1="25.95" x2="5.95" y1="18.589" y2="18.589" gradientUnits="userSpaceOnUse"><stop class="aplr2l3oz"/><stop class="aplr2l3oz"/><stop offset=".444" class="i1wajui0p"/><stop offset=".909" class="ay887kcja"/></linearGradient><linearGradient id="ilwTGwc" x1="28.192" x2="7.262" y1="12.956" y2="12.956" gradientUnits="userSpaceOnUse"><stop class="c5np98r4l"/><stop offset="1" class="fmdp8-b3u"/></linearGradient><linearGradient id="ielAled" x1="17.762" x2="29.95" y1="19.263" y2="12.263" gradientUnits="userSpaceOnUse"><stop class="nbj2lmb5s"/><stop offset="1" class="w6i95b5sr"/></linearGradient><linearGradient id="iMrIIdc" x1="17.443" x2="23.857" y1="13.21" y2="18.458" gradientUnits="userSpaceOnUse"><stop class="xavov8bdl"/><stop offset="1" class="fxnn22bqy"/></linearGradient><linearGradient id="ivOxq7b" x1="17.035" x2="22.079" y1="12.685" y2="17.146" gradientUnits="userSpaceOnUse"><stop class="tq-n4mb-o"/><stop offset="1" class="evhf3i6bx"/></linearGradient><linearGradient id="iZos7gb" x1="17.262" x2="23.387" y1="11.263" y2="23.207" gradientUnits="userSpaceOnUse"><stop class="jl0_zab6n"/><stop offset="1" class="tmak_wb1l"/></linearGradient><linearGradient id="irVNykw" x1="24.273" x2="23.076" y1="18.215" y2="18.304" gradientUnits="userSpaceOnUse"><stop class="enntejbrs"/><stop offset="1" class="fyvnecc-i"/></linearGradient><linearGradient id="iSkCfGb" x1="22.089" x2="21.625" y1="13.321" y2="14.204" gradientUnits="userSpaceOnUse"><stop class="enntejbrs"/><stop offset="1" class="fyvnecc-i"/></linearGradient><linearGradient id="iZwyZyd" x1="21.35" x2="22.866" y1="27.599" y2="27.846" gradientUnits="userSpaceOnUse"><stop class="cu6ii7vcn"/><stop offset="1" class="xcxx2ckvt"/></linearGradient><radialGradient id="inATgVd" cx="0" cy="0" r="1" gradientTransform="rotate(26.959 -13.984 37.948)scale(3.89487 2.42803)" gradientUnits="userSpaceOnUse"><stop class="tarfezbmz"/><stop offset="1" class="m62asebqa"/></radialGradient><radialGradient id="iQXkdXb" cx="0" cy="0" r="1" gradientTransform="rotate(137.337 7.51 16.412)scale(2.07561 2.23528)" gradientUnits="userSpaceOnUse"><stop class="udq4so1rz"/><stop offset="1" class="ehjay13pn"/></radialGradient><radialGradient id="iCMluse" cx="0" cy="0" r="1" gradientTransform="matrix(-3.44037 -1.42864 1.14909 -2.76717 24.44 24.29)" gradientUnits="userSpaceOnUse"><stop offset=".6" class="uq9ztzb6x"/><stop offset=".911" class="z86wvybpp"/></radialGradient><radialGradient id="i53Ii6b" cx="0" cy="0" r="1" gradientTransform="matrix(2.24498 -.34987 .17007 1.0913 21.845 25.076)" gradientUnits="userSpaceOnUse"><stop class="ndcx86bmr"/><stop offset="1" class="dyttiizee"/></radialGradient><radialGradient id="i0hs1zc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.37335 -1.34116 0 24.09 24.727)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="wz6bzjb_t"/><stop offset="1" class="aj22pcbyb"/></radialGradient><radialGradient id="iFR9NZb" cx="0" cy="0" r="1" gradientTransform="matrix(.58311 -2.60156 3.00404 .67332 22.4 30.2)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="f8763bbcj"/><stop offset="1" class="m12bjsh4h"/></radialGradient><filter id="iRWbNRc" width="22.578" height="9.402" x="4.466" y="13.763" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.372549 0 0 0 0 0.658824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17524"/></filter><filter id="ipZO8Ic" width="28.759" height="15.92" x="1" y="4.621" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0980392 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17524"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.372549 0 0 0 0 0.254902 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_17524" result="effect2_innerShadow_18_17524"/></filter><filter id="iF1DVrd" width="14.169" height="8.294" x="15.569" y="11.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17524" stdDeviation=".25"/></filter><filter id="iUp2Tbe" width="9.312" height="7.366" x="14.326" y="11.176" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17524" stdDeviation=".25"/></filter><filter id="iuFZmNN" width="9.112" height="7.166" x="14.934" y="10.693" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17524" stdDeviation=".2"/></filter><filter id="iOgJVQb" width="8.928" height="12.585" x="15.334" y="10.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".15"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.458824 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17524"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:graduation-cap" /></template>
<style>
.aj22pcbyb {
  stop-color: var(--svg-color--ffbc6e, #FFBC6E);
  stop-opacity: 0;
}

.aplr2l3oz {
  stop-color: var(--svg-color--68518b, #68518B);
}

.ay887kcja {
  stop-color: var(--svg-color--35254e, #35254E);
}

.b_iwr5rca {
  d: path("m23.646 16.742l-1.407.717v-.5c0-.667-.087-1.168-.945-1.581l-5.574-2.914a.734.734 0 0 1-.308-.975a.7.7 0 0 1 .95-.317l5.574 2.914a3.23 3.23 0 0 1 1.71 2.656");
}

.c5np98r4l {
  stop-color: var(--svg-color--655676, #655676);
}

.chdi8kbgd {
  d: path("M4.716 14.013h22.328v1.652a7.5 7.5 0 0 1-7.5 7.5h-7.328a7.5 7.5 0 0 1-7.5-7.5z");
}

.cu6ii7vcn {
  stop-color: var(--svg-color--d17047, #D17047);
}

.dvrm_kb6l {
  d: path("M22.419 22.474c-.649.266-.95.823-.95 1.43a1.668 1.668 0 0 0 3.336 0c0-.607-.355-1.149-.941-1.43z");
}

.dyttiizee {
  stop-color: var(--svg-color--fd805e, #FD805E);
  stop-opacity: 0;
}

.ehjay13pn {
  stop-color: var(--svg-color--f49041, #F49041);
}

.enntejbrs {
  stop-color: var(--svg-color--ffd574, #FFD574);
}

.evhf3i6bx {
  stop-color: var(--svg-color--4c2350, #4C2350);
}

.f8763bbcj {
  stop-color: var(--svg-color--ff697e, #FF697E);
}

.fmdp8-b3u {
  stop-color: var(--svg-color--2d2635, #2D2635);
}

.ft5dv1b6b {
  fill: none;
}

.fxnn22bqy {
  stop-color: var(--svg-color--3d2c43, #3D2C43);
  stop-opacity: 0;
}

.fyvnecc-i {
  stop-color: var(--svg-color--ffd574, #FFD574);
  stop-opacity: 0;
}

.i1wajui0p {
  stop-color: var(--svg-color--503678, #503678);
}

.jl0_zab6n {
  stop-color: var(--svg-color--d3a543, #D3A543);
}

.m12bjsh4h {
  stop-color: var(--svg-color--ff697e, #FF697E);
  stop-opacity: 0;
}

.m62asebqa {
  stop-color: var(--svg-color--d0a745, #D0A745);
  stop-opacity: 0;
}

.nbj2lmb5s {
  stop-color: var(--svg-color--6e5f85, #6E5F85);
}

.ndcx86bmr {
  stop-color: var(--svg-color--fd805e, #FD805E);
}

.noqswdaov {
  fill-rule: evenodd;
  d: path("M15.414 11.168a.725.725 0 0 1 .975-.316l5.714 2.913a3.23 3.23 0 0 1 1.76 2.873v5.844a.725.725 0 0 1-1.45 0v-5.844c0-.667-.375-1.278-.97-1.58l-5.713-2.915a.725.725 0 0 1-.316-.975");
}

.qyq_t6hnx {
  d: path("m15.289 20.399l-12.69-6.482a1.1 1.1 0 0 1 .003-1.96L15.29 5.512a1.3 1.3 0 0 1 1.179 0l12.69 6.46a1.1 1.1 0 0 1 0 1.96L16.47 20.399a1.3 1.3 0 0 1-1.182 0");
}

.tarfezbmz {
  stop-color: var(--svg-color--d0a745, #D0A745);
}

.tb5su8b4w {
  d: path("m21.226 27.647l.638-2.65h2.527l.652 2.627a1.994 1.994 0 0 1-1.905 2.577a1.992 1.992 0 0 1-1.912-2.554");
}

.tmak_wb1l {
  stop-color: var(--svg-color--ffba62, #FFBA62);
}

.tq-n4mb-o {
  stop-color: var(--svg-color--2c1a20, #2C1A20);
}

.udq4so1rz {
  stop-color: var(--svg-color--ffcc6c, #FFCC6C);
}

.uq9ztzb6x {
  stop-color: var(--svg-color--b25d41, #B25D41);
  stop-opacity: 0;
}

.vta_up4os {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-7px, 0.7px);
  d: path("m16.419 19.263l12.468-6.594");
}

.w6i95b5sr {
  stop-color: var(--svg-color--9a8da7, #9A8DA7);
}

.wz6bzjb_t {
  stop-color: var(--svg-color--ffbc6e, #FFBC6E);
}

.x_ki2cbos {
  fill: var(--svg-color--ff9d4e, #FF9D4E);
  d: path("m21.226 27.647l.638-2.65h2.527l.652 2.627a1.994 1.994 0 0 1-1.905 2.577a1.992 1.992 0 0 1-1.912-2.554");
}

.xavov8bdl {
  stop-color: var(--svg-color--3c2d42, #3C2D42);
}

.xcxx2ckvt {
  stop-color: var(--svg-color--d17047, #D17047);
  stop-opacity: 0;
}

.z69tstf1u {
  d: path("m23.137 17.325l-1.407.717v-.5c0-.667-.087-1.168-.945-1.581l-5.573-2.914a.734.734 0 0 1-.309-.975a.7.7 0 0 1 .951-.316l5.574 2.913a3.23 3.23 0 0 1 1.71 2.656");
}

.z86wvybpp {
  stop-color: var(--svg-color--b25d41, #B25D41);
}

</style>
