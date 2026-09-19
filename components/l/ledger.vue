<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#igihTXb)"><rect fill="url(#iQQOobe)" class="j2wu18wfq"/><rect fill="url(#iXMJ8HQ)" class="j2wu18wfq"/></g><g filter="url(#iffsbZc)"><rect fill="url(#iVQQype)" class="hf_s33b_p"/></g><g filter="url(#iXa2NUP)"><rect fill="url(#i5jjAsd)" class="l3qc9dnbt"/></g><rect fill="url(#iaEbTab)" class="gtdhpe7mk"/><g filter="url(#ieAkO8b)"><path fill="url(#irMMLle)" class="kn65ep1ac"/></g><g filter="url(#i4Q5xYb)"><path fill="url(#iP6VGGb)" class="roex9mb0a"/></g><g filter="url(#i5orEMr)"><path fill="url(#iryyOne)" class="eklpm0bar"/></g><g filter="url(#iFo41me)"><path fill="url(#ikiaFZZ)" class="ahouq4alk"/></g><path fill="url(#izqPCBc)" class="xd-yybb3o"/><path fill="url(#iXeTByd)" class="xd-yybb3o"/><path fill="url(#iopM1dd)" class="xd-yybb3o"/><path fill="url(#iUgI03z)" class="lii99bnwl"/><path fill="url(#iGkFzmd)" class="lii99bnwl"/><path fill="url(#iXQlMEd)" class="lii99bnwl"/><path fill="url(#iTkhCge)" class="ngewg_qcz"/><path fill="url(#iLqQWve)" class="ngewg_qcz"/><path fill="url(#igzaaBd)" class="ngewg_qcz"/><path fill="url(#iX40S1d)" class="uyvw6hbnd"/><path fill="url(#itpDiNz)" class="uyvw6hbnd"/><path fill="url(#iQjHTze)" class="uyvw6hbnd"/><g filter="url(#ixShypc)"><path stroke="url(#iwsWlsc)" class="pob54zbqy"/></g><g filter="url(#iz68iUD)"><path stroke="url(#iZGqFYc)" class="wlkh_8b9x"/></g><g filter="url(#iR6MAwc)"><path stroke="url(#iGvfvub)" class="sid2qbh8f"/></g><g filter="url(#ikMdbMd)"><path stroke="url(#i8Yg40g)" class="ttoubq2dr"/></g><defs><radialGradient id="iXMJ8HQ" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.5625 -2.35866 0 6.574 25.828)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="io64idspi"/><stop offset="1" class="hxq9xq7rw"/></radialGradient><radialGradient id="iXeTByd" cx="0" cy="0" r="1" gradientTransform="matrix(-.26265 -2.73838 3.08684 -.29608 6.433 6.281)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="rgdpzwb4p"/><stop offset="1" class="z6jxrbb1q"/></radialGradient><radialGradient id="iopM1dd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.12503 3.68749 -3.4187 -1.97013 7.012 5.313)" gradientUnits="userSpaceOnUse"><stop offset=".708" class="iz7le238t"/><stop offset="1" class="qodiypbxw"/></radialGradient><radialGradient id="iGkFzmd" cx="0" cy="0" r="1" gradientTransform="matrix(-.26265 -2.73838 3.08684 -.29608 6.433 11.418)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="rgdpzwb4p"/><stop offset="1" class="z6jxrbb1q"/></radialGradient><radialGradient id="iXQlMEd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.12503 3.68749 -3.4187 -1.97013 7.012 10.45)" gradientUnits="userSpaceOnUse"><stop offset=".708" class="iz7le238t"/><stop offset="1" class="qodiypbxw"/></radialGradient><radialGradient id="iLqQWve" cx="0" cy="0" r="1" gradientTransform="matrix(-.26265 -2.73838 3.08684 -.29608 6.433 16.578)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="rgdpzwb4p"/><stop offset="1" class="z6jxrbb1q"/></radialGradient><radialGradient id="igzaaBd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.12503 3.68749 -3.4187 -1.97013 7.012 15.61)" gradientUnits="userSpaceOnUse"><stop offset=".708" class="iz7le238t"/><stop offset="1" class="qodiypbxw"/></radialGradient><radialGradient id="itpDiNz" cx="0" cy="0" r="1" gradientTransform="matrix(-.26265 -2.73838 3.08684 -.29608 6.433 21.727)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="rgdpzwb4p"/><stop offset="1" class="z6jxrbb1q"/></radialGradient><radialGradient id="iQjHTze" cx="0" cy="0" r="1" gradientTransform="matrix(-2.12503 3.68749 -3.4187 -1.97013 7.012 20.758)" gradientUnits="userSpaceOnUse"><stop offset=".708" class="iz7le238t"/><stop offset="1" class="qodiypbxw"/></radialGradient><radialGradient id="iwsWlsc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.18749 2.09376 -2.85426 -1.6188 7.918 13.61)" gradientUnits="userSpaceOnUse"><stop class="y_z94c05g"/><stop offset="1" class="o25i1gbjc"/></radialGradient><radialGradient id="iZGqFYc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.18749 2.09376 -2.85426 -1.6188 7.918 8.46)" gradientUnits="userSpaceOnUse"><stop class="y_z94c05g"/><stop offset="1" class="o25i1gbjc"/></radialGradient><radialGradient id="iGvfvub" cx="0" cy="0" r="1" gradientTransform="matrix(-1.18749 2.09376 -2.85426 -1.6188 7.918 3.313)" gradientUnits="userSpaceOnUse"><stop class="y_z94c05g"/><stop offset="1" class="o25i1gbjc"/></radialGradient><radialGradient id="i8Yg40g" cx="0" cy="0" r="1" gradientTransform="matrix(-1.18749 2.09376 -2.85426 -1.6188 7.918 18.758)" gradientUnits="userSpaceOnUse"><stop class="y_z94c05g"/><stop offset="1" class="o25i1gbjc"/></radialGradient><linearGradient id="iQQOobe" x1="29.762" x2="20.199" y1="28.891" y2="28.891" gradientUnits="userSpaceOnUse"><stop class="d3jwugb_l"/><stop offset="1" class="ew1kjabjq"/></linearGradient><linearGradient id="iVQQype" x1="17.434" x2="17.434" y1="26.703" y2="28.797" gradientUnits="userSpaceOnUse"><stop class="w-wsrvimt"/><stop offset="1" class="w6ydrbbdc"/></linearGradient><linearGradient id="i5jjAsd" x1="17.434" x2="17.434" y1="2.047" y2="26.797" gradientUnits="userSpaceOnUse"><stop class="vnn042ybf"/><stop offset="1" class="vj4m2tb3q"/></linearGradient><linearGradient id="iaEbTab" x1="17.465" x2="17.465" y1="8.545" y2="11.516" gradientUnits="userSpaceOnUse"><stop class="w15gtbiil"/><stop offset="1" class="y35kqz9gt"/></linearGradient><linearGradient id="irMMLle" x1="9.043" x2="3.699" y1="22.234" y2="20.609" gradientUnits="userSpaceOnUse"><stop offset=".231" class="v3asvbbuc"/><stop offset="1" class="srz4f7byn"/></linearGradient><linearGradient id="iP6VGGb" x1="9.043" x2="3.699" y1="17.18" y2="15.555" gradientUnits="userSpaceOnUse"><stop offset=".231" class="tywrozgnd"/><stop offset="1" class="o81j8762n"/></linearGradient><linearGradient id="iryyOne" x1="9.043" x2="3.699" y1="12.125" y2="10.5" gradientUnits="userSpaceOnUse"><stop offset=".231" class="tywrozgnd"/><stop offset="1" class="o81j8762n"/></linearGradient><linearGradient id="ikiaFZZ" x1="9.043" x2="3.699" y1="6.883" y2="5.258" gradientUnits="userSpaceOnUse"><stop offset=".231" class="o42ikzf4j"/><stop offset="1" class="onoj7wbfm"/></linearGradient><linearGradient id="izqPCBc" x1="6.433" x2="6.433" y1="3.019" y2="9.567" gradientUnits="userSpaceOnUse"><stop class="rnm0ksbdp"/><stop offset="1" class="jnul6q2fk"/></linearGradient><linearGradient id="iUgI03z" x1="6.433" x2="6.433" y1="8.156" y2="14.704" gradientUnits="userSpaceOnUse"><stop class="rnm0ksbdp"/><stop offset="1" class="jnul6q2fk"/></linearGradient><linearGradient id="iTkhCge" x1="6.433" x2="6.433" y1="13.316" y2="19.864" gradientUnits="userSpaceOnUse"><stop class="rnm0ksbdp"/><stop offset="1" class="jnul6q2fk"/></linearGradient><linearGradient id="iX40S1d" x1="6.433" x2="6.433" y1="18.464" y2="25.012" gradientUnits="userSpaceOnUse"><stop class="rnm0ksbdp"/><stop offset="1" class="jnul6q2fk"/></linearGradient><filter id="igihTXb" width="22.781" height="24.9" x="6.043" y="5.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.568627 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20934"/></filter><filter id="iffsbZc" width="21.381" height="23.694" x="6.443" y="5.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy="-.1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.898039 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20934"/></filter><filter id="iXa2NUP" width="22.881" height="24.95" x="5.943" y="1.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.556863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20934"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.87451 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_20934" result="effect2_innerShadow_18_20934"/></filter><filter id="ieAkO8b" width="4.105" height="2.996" x="5.776" y="19.803" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20934" stdDeviation=".2"/></filter><filter id="i4Q5xYb" width="4.105" height="2.996" x="5.776" y="14.748" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20934" stdDeviation=".2"/></filter><filter id="i5orEMr" width="4.105" height="2.996" x="5.776" y="9.694" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20934" stdDeviation=".2"/></filter><filter id="iFo41me" width="4.105" height="2.996" x="5.776" y="4.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20934" stdDeviation=".2"/></filter><filter id="ixShypc" width="6.339" height="6.348" x="3.263" y="13.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20934" stdDeviation=".2"/></filter><filter id="iz68iUD" width="6.339" height="6.348" x="3.263" y="8.037" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20934" stdDeviation=".2"/></filter><filter id="iR6MAwc" width="6.339" height="6.348" x="3.263" y="2.888" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20934" stdDeviation=".2"/></filter><filter id="ikMdbMd" width="6.339" height="6.348" x="3.263" y="18.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20934" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ledger" /></template>
<style>
.ahouq4alk {
  d: path("m6.176 4.852l2.762.75a.735.735 0 0 1-.386 1.419l-2.376-.646z");
}

.d3jwugb_l {
  stop-color: var(--svg-color--ffdc34, #FFDC34);
}

.eklpm0bar {
  d: path("m6.176 10.094l2.762.75a.735.735 0 0 1-.386 1.419l-2.376-.646z");
}

.ew1kjabjq {
  stop-color: var(--svg-color--e6b42f, #E6B42F);
}

.ft5dv1b6b {
  fill: none;
}

.gtdhpe7mk {
  width: 10.281px;
  height: 3.766px;
  x: 12.324px;
  y: 7.75px;
  rx: 1px;
}

.hf_s33b_p {
  width: 20.781px;
  height: 23.594px;
  x: 7.043px;
  y: 5.203px;
  rx: 1.2px;
}

.hxq9xq7rw {
  stop-color: var(--svg-color--d1a02d, #D1A02D);
  stop-opacity: 0;
}

.io64idspi {
  stop-color: var(--svg-color--d1a02d, #D1A02D);
}

.iz7le238t {
  stop-color: var(--svg-color--aa9db4, #AA9DB4);
  stop-opacity: 0;
}

.j2wu18wfq {
  width: 22.781px;
  height: 24.75px;
  x: 6.043px;
  y: 5.203px;
  rx: 1px;
}

.jnul6q2fk {
  stop-color: var(--svg-color--a498ad, #A498AD);
}

.kn65ep1ac {
  d: path("m6.176 20.203l2.762.751a.735.735 0 1 1-.386 1.418l-2.376-.645z");
}

.l3qc9dnbt {
  width: 22.781px;
  height: 24.75px;
  x: 6.043px;
  y: 2.047px;
  rx: 1px;
}

.lii99bnwl {
  d: path("M4.563 11.43a1.874 1.874 0 0 1 3.742-.159a.7.7 0 0 0 1.395-.116a3.274 3.274 0 1 0-3.657 3.525v-1.418a1.875 1.875 0 0 1-1.48-1.832");
}

.ngewg_qcz {
  d: path("M4.563 16.59a1.874 1.874 0 0 1 3.742-.159a.7.7 0 0 0 1.395-.116a3.274 3.274 0 1 0-3.657 3.526v-1.419a1.875 1.875 0 0 1-1.48-1.832");
}

.o25i1gbjc {
  stop-color: var(--svg-color--ddd7dd, #DDD7DD);
  stop-opacity: 0;
}

.o42ikzf4j {
  stop-color: var(--svg-color--d6b32c, #D6B32C);
}

.o81j8762n {
  stop-color: var(--svg-color--d8ad2e, #D8AD2E);
  stop-opacity: 0;
}

.onoj7wbfm {
  stop-color: var(--svg-color--d6b32c, #D6B32C);
  stop-opacity: 0;
}

.pob54zbqy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M6.438 18.934a2.574 2.574 0 1 1 2.565-2.791");
}

.qodiypbxw {
  stop-color: var(--svg-color--8d7f98, #8D7F98);
}

.rgdpzwb4p {
  stop-color: var(--svg-color--b8a5bd, #B8A5BD);
}

.rnm0ksbdp {
  stop-color: var(--svg-color--c7c4ca, #C7C4CA);
}

.roex9mb0a {
  d: path("m6.176 15.148l2.762.752a.735.735 0 0 1-.386 1.419l-2.376-.647z");
}

.sid2qbh8f {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M6.438 8.637a2.574 2.574 0 1 1 2.565-2.791");
}

.srz4f7byn {
  stop-color: var(--svg-color--dbab35, #DBAB35);
  stop-opacity: 0;
}

.ttoubq2dr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M6.438 24.082a2.574 2.574 0 1 1 2.565-2.79");
}

.tywrozgnd {
  stop-color: var(--svg-color--d8ad2e, #D8AD2E);
}

.uyvw6hbnd {
  d: path("M4.563 21.738a1.874 1.874 0 0 1 3.742-.158a.7.7 0 0 0 1.395-.116a3.274 3.274 0 1 0-3.657 3.525v-1.418a1.875 1.875 0 0 1-1.48-1.833");
}

.v3asvbbuc {
  stop-color: var(--svg-color--d39d2c, #D39D2C);
}

.vj4m2tb3q {
  stop-color: var(--svg-color--ffd336, #FFD336);
}

.vnn042ybf {
  stop-color: var(--svg-color--ffea3a, #FFEA3A);
}

.w-wsrvimt {
  stop-color: var(--svg-color--d1b0e9, #D1B0E9);
}

.w15gtbiil {
  stop-color: var(--svg-color--ffd046, #FFD046);
}

.w6ydrbbdc {
  stop-color: var(--svg-color--e4c1ea, #E4C1EA);
}

.wlkh_8b9x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M6.438 13.785a2.574 2.574 0 1 1 2.565-2.79");
}

.xd-yybb3o {
  d: path("M4.563 6.293a1.874 1.874 0 0 1 3.742-.159a.7.7 0 1 0 1.395-.116a3.274 3.274 0 1 0-3.657 3.526V8.126a1.875 1.875 0 0 1-1.48-1.833");
}

.y_z94c05g {
  stop-color: var(--svg-color--ddd7dd, #DDD7DD);
}

.y35kqz9gt {
  stop-color: var(--svg-color--ffbc41, #FFBC41);
}

.z6jxrbb1q {
  stop-color: var(--svg-color--b8a5bd, #B8A5BD);
  stop-opacity: 0;
}

</style>
