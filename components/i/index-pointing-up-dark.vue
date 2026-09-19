<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iSrC86c)"><path class="n4awb_lbu"/></g><path fill="url(#iMxkr1b)" class="z_7vmrp7r"/><path fill="url(#iwH212b)" class="z_7vmrp7r"/><path fill="url(#imqI8Dd)" class="z_7vmrp7r"/><path fill="url(#il3jqee)" class="z_7vmrp7r"/><path fill="url(#ijkvqGb)" class="z_7vmrp7r"/><g filter="url(#i8L968c)"><path class="qx36171gz"/></g><g filter="url(#imTykVc)"><path class="xbtfj-5-t"/></g><g filter="url(#i2TJgHe)"><path class="fge2hxoxn"/></g><g filter="url(#ilWXvfj)"><path fill="url(#iQD7hrr)" class="jayro6-nm"/><path fill="url(#ier4Sbo)" class="jayro6-nm"/></g><path fill="url(#iPC45fe)" class="jayro6-nm"/><path fill="url(#iq5xC4b)" class="jayro6-nm"/><g filter="url(#ihyoPQr)"><path fill="url(#i4qiBbd)" class="t2fuhi4hu"/><path fill="url(#isp9qxd)" class="t2fuhi4hu"/><path fill="url(#iVrstbe)" class="t2fuhi4hu"/><path fill="url(#icqVGud)" class="t2fuhi4hu"/></g><g filter="url(#iQaLV1b)"><path fill="url(#iOh8hQb)" class="v793vk6no"/></g><g filter="url(#iunqz3h)"><rect transform="rotate(-3.35 8.302 13.938)" class="grqttv7si"/></g><g filter="url(#iCHLBlb)"><rect fill="url(#iVVTkrd)" transform="rotate(-1.407 12.867 11.684)" class="ta7q-6sbq"/></g><g filter="url(#i0HraRc)"><rect transform="rotate(-1.407 18.129 11.366)" class="gt-dlpb0e"/></g><path fill="url(#ifiRrKF)" class="j8y654c_u"/><path fill="url(#iCQ56Tc)" class="j8y654c_u"/><path fill="url(#iTtoL2d)" class="j8y654c_u"/><g filter="url(#i0ZSmMb)"><path stroke="url(#ioavhkd)" class="zjzilibto"/></g><g filter="url(#iSsHz1c)"><rect class="cvq1vlxlq"/></g><defs><filter id="iSrC86c" width="20.934" height="28.788" x="5.684" y="1.183" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6" dy="-.6"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.12549 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5580"/></filter><filter id="i8L968c" width="14.516" height="10.203" x="12.258" y="13.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5580" stdDeviation="1.25"/></filter><filter id="imTykVc" width="9.153" height="11.219" x="4.823" y="11.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5580" stdDeviation="1.25"/></filter><filter id="i2TJgHe" width="9.825" height="12.747" x="8.675" y="10.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5580" stdDeviation="1.25"/></filter><filter id="ilWXvfj" width="5.431" height="8.136" x="5.684" y="11.971" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.101961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5580"/></filter><filter id="ihyoPQr" width="5.272" height="8.719" x="10.532" y="10.743" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0745098 0 0 0 0 0.0666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5580"/></filter><filter id="iQaLV1b" width="5.414" height="9.427" x="15.662" y="10.035" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0745098 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5580"/></filter><filter id="iunqz3h" width="4.869" height="7.227" x="6.851" y="12.387" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5580" stdDeviation=".75"/></filter><filter id="iCHLBlb" width="5.019" height="8.302" x="11.391" y="10.16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5580" stdDeviation=".75"/></filter><filter id="i0HraRc" width="5.045" height="9.019" x="16.652" y="9.841" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5580" stdDeviation=".75"/></filter><filter id="i0ZSmMb" width="8.894" height="7.704" x="17.114" y="15.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5580" stdDeviation=".625"/></filter><filter id="iSsHz1c" width="5.688" height="15.594" x="21.195" y="1.408" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5580" stdDeviation="1"/></filter><radialGradient id="iMxkr1b" cx="0" cy="0" r="1" gradientTransform="matrix(-6.56216 -6.90397 4.82919 -4.5901 25.445 17.125)" gradientUnits="userSpaceOnUse"><stop class="w-l5r38ro"/><stop offset="1" class="ij4r6cc7j"/></radialGradient><radialGradient id="iwH212b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.86066 3.08361 -3.55273 -3.29586 20.43 21.063)" gradientUnits="userSpaceOnUse"><stop class="e5t-36bmz"/><stop offset="1" class="w_o6w8bni"/></radialGradient><radialGradient id="il3jqee" cx="0" cy="0" r="1" gradientTransform="matrix(-1 1.28124 -1.43471 -1.1198 24.164 3.752)" gradientUnits="userSpaceOnUse"><stop class="eser-fblc"/><stop offset="1" class="v41ltixcj"/></radialGradient><radialGradient id="ijkvqGb" cx="0" cy="0" r="1" gradientTransform="matrix(2.61097 0 0 5.50045 20.023 12.894)" gradientUnits="userSpaceOnUse"><stop class="z9z385u3p"/><stop offset="1" class="ru44dhggk"/></radialGradient><radialGradient id="iPC45fe" cx="0" cy="0" r="1" gradientTransform="matrix(.49402 -1.84138 2.37393 .6369 7.522 20.288)" gradientUnits="userSpaceOnUse"><stop class="cdecbxa-k"/><stop offset="1" class="w3_2bn_mn"/></radialGradient><radialGradient id="iq5xC4b" cx="0" cy="0" r="1" gradientTransform="rotate(163.749 4.612 7.415)scale(1.10333 2.13513)" gradientUnits="userSpaceOnUse"><stop class="z_w-3qbvr"/><stop offset="1" class="ft8_jrbyg"/></radialGradient><radialGradient id="iVrstbe" cx="0" cy="0" r="1" gradientTransform="rotate(-82.532 17.366 2.578)scale(3.14412 4.97212)" gradientUnits="userSpaceOnUse"><stop class="d0nwchb2m"/><stop offset="1" class="idxxgab-m"/></radialGradient><radialGradient id="icqVGud" cx="0" cy="0" r="1" gradientTransform="matrix(-.67768 .30875 -.56066 -1.2306 15.804 12.577)" gradientUnits="userSpaceOnUse"><stop class="dyje4o-xz"/><stop offset="1" class="bno8c_yas"/></radialGradient><radialGradient id="iVVTkrd" cx="0" cy="0" r="1" gradientTransform="rotate(91.407 .171 13.676)scale(7.23413 3.88646)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="iCQ56Tc" cx="0" cy="0" r="1" gradientTransform="matrix(3.40306 3.0913 -2.37051 2.60958 19.62 21.81)" gradientUnits="userSpaceOnUse"><stop class="qdcjv9bcw"/><stop offset="1" class="hrhmmibyl"/></radialGradient><linearGradient id="imqI8Dd" x1="26.82" x2="23.086" y1="12.096" y2="12.096" gradientUnits="userSpaceOnUse"><stop class="t7jp26p8q"/><stop offset="1" class="z8c9pnbtn"/></linearGradient><linearGradient id="iQD7hrr" x1="8.4" x2="8.4" y1="12.315" y2="19.408" gradientUnits="userSpaceOnUse"><stop class="yd6vs-kvu"/><stop offset="1" class="lvlod4-sl"/></linearGradient><linearGradient id="ier4Sbo" x1="11.445" x2="9.683" y1="15.598" y2="15.714" gradientUnits="userSpaceOnUse"><stop class="y4c8qjb2h"/><stop offset="1" class="v35btechu"/></linearGradient><linearGradient id="i4qiBbd" x1="15.559" x2="10.809" y1="14.315" y2="14.783" gradientUnits="userSpaceOnUse"><stop class="ocfm3ob4h"/><stop offset="1" class="e8twlgblt"/><stop offset="1" class="sgbublbsx"/></linearGradient><linearGradient id="isp9qxd" x1="16.124" x2="14.412" y1="14.63" y2="14.732" gradientUnits="userSpaceOnUse"><stop class="qeoin4b7e"/><stop offset="1" class="igvl_33kk"/></linearGradient><linearGradient id="iOh8hQb" x1="16.653" x2="20.72" y1="13.745" y2="13.745" gradientUnits="userSpaceOnUse"><stop class="jji4ghbxr"/><stop offset="1" class="fspy8rbwh"/></linearGradient><linearGradient id="ifiRrKF" x1="24.175" x2="20.542" y1="17.055" y2="21.806" gradientUnits="userSpaceOnUse"><stop class="e6-2kysgc"/><stop offset="1" class="ux17cemhq"/></linearGradient><linearGradient id="iTtoL2d" x1="22.555" x2="22.519" y1="26.161" y2="22.094" gradientUnits="userSpaceOnUse"><stop offset=".382" class="iulurhe8a"/><stop offset="1" class="m122378lg"/></linearGradient><linearGradient id="ioavhkd" x1="21.039" x2="24.547" y1="17.658" y2="20.274" gradientUnits="userSpaceOnUse"><stop offset=".452" class="a5c9r5b5q"/><stop offset="1" class="tahqmyqsp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:index-pointing-up-dark" /></template>
<style>
.a5c9r5b5q {
  stop-color: var(--svg-color--64504e, #64504E);
}

.bno8c_yas {
  stop-color: var(--svg-color--2d1b17, #2D1B17);
  stop-opacity: 0;
}

.cdecbxa-k {
  stop-color: var(--svg-color--381f2d, #381F2D);
}

.cvq1vlxlq {
  width: 1.688px;
  height: 11.594px;
  x: 23.195px;
  y: 3.408px;
  fill: var(--svg-color--65514f, #65514F);
  rx: 0.844px;
}

.d0nwchb2m {
  stop-color: var(--svg-color--3a1f2c, #3A1F2C);
}

.dyje4o-xz {
  stop-color: var(--svg-color--2d1b17, #2D1B17);
}

.e5t-36bmz {
  stop-color: var(--svg-color--3d282e, #3D282E);
}

.e6-2kysgc {
  stop-color: var(--svg-color--533834, #533834);
}

.e8twlgblt {
  stop-color: var(--svg-color--402d2a, #402D2A);
}

.eser-fblc {
  stop-color: var(--svg-color--675250, #675250);
}

.fge2hxoxn {
  fill: var(--svg-color--221219, #221219);
  d: path("M11.175 15.535c0-1.294 1.08-2.343 2.412-2.343c1.333 0 2.413 1.049 2.413 2.342v3.063c0 1.294-1.08 2.342-2.413 2.342s-2.218-.67-2.218-2.083z");
}

.fspy8rbwh {
  stop-color: var(--svg-color--5a403d, #5A403D);
}

.ft5dv1b6b {
  fill: none;
}

.ft8_jrbyg {
  stop-color: var(--svg-color--1b0e0c, #1B0E0C);
  stop-opacity: 0;
}

.grqttv7si {
  width: 1.722px;
  height: 4.231px;
  x: 8.302px;
  y: 13.938px;
  fill: var(--svg-color--63504e, #63504E);
  rx: 0.861px;
}

.gt-dlpb0e {
  width: 1.945px;
  height: 6.02px;
  x: 18.129px;
  y: 11.366px;
  fill: var(--svg-color--675250, #675250);
  rx: 0.973px;
}

.hrhmmibyl {
  stop-color: var(--svg-color--3b202f, #3B202F);
  stop-opacity: 0;
}

.idxxgab-m {
  stop-color: var(--svg-color--3a1f2c, #3A1F2C);
  stop-opacity: 0;
}

.igvl_33kk {
  stop-color: var(--svg-color--36211e, #36211E);
  stop-opacity: 0;
}

.ij4r6cc7j {
  stop-color: var(--svg-color--64514f, #64514F);
  stop-opacity: 0;
}

.iulurhe8a {
  stop-color: var(--svg-color--452b33, #452B33);
}

.j8y654c_u {
  d: path("M18.27 15.158c-1.388 0-2.512 1.162-2.512 2.594c0 1.433 1.124 2.594 2.512 2.594h.105c.821 0 1.64.317 2.067 1.02a6 6 0 0 1 .874 3.136c0 .878-.186 1.712-.521 2.463c2.598-.625 4.531-2.995 4.531-5.822c0-2.492-1.597-4.686-3.733-5.587a3.4 3.4 0 0 0-1.008-.288z");
}

.jayro6-nm {
  d: path("M5.684 14.477c0-1.382 1.102-2.412 2.503-2.502c1.302-.063 2.596.735 2.707 2.323l.215 3.013c.108 1.51-1.3 2.796-2.815 2.796a2.61 2.61 0 0 1-2.61-2.61z");
}

.jji4ghbxr {
  stop-color: var(--svg-color--3f2b29, #3F2B29);
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.lvlod4-sl {
  stop-color: var(--svg-color--42292d, #42292D);
}

.m122378lg {
  stop-color: var(--svg-color--452b33, #452B33);
  stop-opacity: 0;
}

.n4awb_lbu {
  fill: var(--svg-color--462c33, #462C33);
  d: path("M23.136 1.783A2.656 2.656 0 0 0 20.48 4.44v11.25H5.684v4.227c0 5.552 4.502 10.054 10.054 10.054c4.243 0 7.873-2.629 9.348-6.346l.003.002c1.016-2.39 1.016-6.703.844-7.86a12 12 0 0 1-.14-1.496V4.44a2.656 2.656 0 0 0-2.657-2.656");
}

.ocfm3ob4h {
  stop-color: var(--svg-color--533b37, #533B37);
}

.qdcjv9bcw {
  stop-color: var(--svg-color--3b202f, #3B202F);
}

.qeoin4b7e {
  stop-color: var(--svg-color--36211e, #36211E);
}

.qx36171gz {
  fill: var(--svg-color--221219, #221219);
  d: path("M14.758 18.752c0-1.432 1.124-2.594 2.512-2.594l2.315.11c.346.042.69.14 1.008.288c1.91.805 3.389 2.644 3.68 4.805h-6.585a3 3 0 0 0-.313-.015h-.105c-1.388 0-2.512-1.162-2.512-2.594");
}

.ru44dhggk {
  stop-color: var(--svg-color--271210, #271210);
  stop-opacity: 0;
}

.sgbublbsx {
  stop-color: var(--svg-color--3f2929, #3F2929);
}

.t2fuhi4hu {
  d: path("M10.532 13.38a2.636 2.636 0 0 1 5.272 0v3.446a2.636 2.636 0 0 1-2.636 2.636c-1.456 0-2.424-.756-2.424-2.345z");
}

.t7jp26p8q {
  stop-color: var(--svg-color--5b4340, #5B4340);
}

.ta7q-6sbq {
  width: 1.936px;
  height: 5.303px;
  x: 12.867px;
  y: 11.684px;
  rx: 0.968px;
}

.tahqmyqsp {
  stop-color: var(--svg-color--64504e, #64504E);
  stop-opacity: 0;
}

.ux17cemhq {
  stop-color: var(--svg-color--3e272a, #3E272A);
}

.v35btechu {
  stop-color: var(--svg-color--2b1917, #2B1917);
  stop-opacity: 0;
}

.v41ltixcj {
  stop-color: var(--svg-color--675250, #675250);
  stop-opacity: 0;
}

.v793vk6no {
  d: path("M15.662 12.885c0-1.574 1.212-2.85 2.707-2.85s2.707 1.276 2.707 2.85v3.727c0 1.574-1.212 2.85-2.707 2.85s-2.707-.732-2.707-2.45z");
}

.w_o6w8bni {
  stop-color: var(--svg-color--3d282e, #3D282E);
  stop-opacity: 0;
}

.w-l5r38ro {
  stop-color: var(--svg-color--64514f, #64514F);
}

.w3_2bn_mn {
  stop-color: var(--svg-color--381f2d, #381F2D);
  stop-opacity: 0;
}

.xbtfj-5-t {
  fill: var(--svg-color--221219, #221219);
  d: path("M7.323 15.98c0-1.057.843-1.844 1.914-1.913c.996-.048 1.986.563 2.07 1.776l.165 2.303c.083 1.155-.994 2.137-2.153 2.137a1.996 1.996 0 0 1-1.996-1.995z");
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.y4c8qjb2h {
  stop-color: var(--svg-color--2b1917, #2B1917);
}

.yd6vs-kvu {
  stop-color: var(--svg-color--543f3c, #543F3C);
}

.z_7vmrp7r {
  d: path("M23.136 1.783A2.656 2.656 0 0 0 20.48 4.44v11.25H5.684v4.227c0 5.552 4.502 10.054 10.054 10.054c4.243 0 7.873-2.629 9.348-6.346l.003.002c1.016-2.39 1.016-6.703.844-7.86a12 12 0 0 1-.14-1.496V4.44a2.656 2.656 0 0 0-2.657-2.656");
}

.z_w-3qbvr {
  stop-color: var(--svg-color--1b0e0c, #1B0E0C);
}

.z8c9pnbtn {
  stop-color: var(--svg-color--5b4340, #5B4340);
  stop-opacity: 0;
}

.z9z385u3p {
  stop-color: var(--svg-color--271210, #271210);
}

.zjzilibto {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M18.989 16.986c1.201 0 3.21 0 3.946.945c1.075 1.052 1.137 2.589 1.198 3.008");
}

</style>
