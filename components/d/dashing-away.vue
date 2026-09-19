<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ik5rUnb)" class="ibv8g_bhn"/><path fill="url(#iHLJied)" class="ibv8g_bhn"/><path fill="url(#iVPV2ye)" class="ibv8g_bhn"/><path fill="url(#ik9LpPe)" class="ibv8g_bhn"/><path fill="url(#iYtMhab)" class="ibv8g_bhn"/><path fill="url(#iRPqlxb)" class="ibv8g_bhn"/><path fill="url(#iTXwjLe)" class="ibv8g_bhn"/><path fill="url(#i0mrpcc)" class="ogtyo31au"/><path fill="url(#it61IRc)" class="dh5e3bmbz"/><circle fill="url(#iQGq3nb)" class="z_9vl-bwa"/><circle fill="url(#immogNd)" class="z_9vl-bwa"/><circle fill="url(#iUmMFmb)" class="z_9vl-bwa"/><circle fill="url(#il9cZje)" class="qv-q-dbaw"/><circle fill="url(#iXrWZwe)" class="qv-q-dbaw"/><circle fill="url(#iqOO73c)" class="qv-q-dbaw"/><circle fill="url(#iwjsO4c)" class="yg15wcy7d"/><circle fill="url(#iEwzYup)" class="yg15wcy7d"/><g filter="url(#idQKgJe)"><circle fill="url(#iv7onwb)" class="uz03lkm3d"/><circle fill="url(#icgocRb)" class="uz03lkm3d"/><circle fill="url(#ipxD2Ib)" class="uz03lkm3d"/></g><g filter="url(#i7oKnGd)"><circle fill="url(#iHuE43d)" class="n72quk_el"/></g><g filter="url(#i7oKnGd)"><circle fill="url(#iQGQlLr)" class="n72quk_el"/></g><g filter="url(#ifeAyzc)"><path fill="url(#iMfrNgo)" class="yqacpthxm"/><path fill="url(#i4SxLfP)" class="yqacpthxm"/><path fill="url(#iwbeASb)" class="yqacpthxm"/><path fill="url(#isHbAHb)" class="yqacpthxm"/></g><g filter="url(#i0FwgVe)"><path stroke="url(#iuzFwed)" class="pcr86sbvm"/></g><g filter="url(#iANZTwc)"><path class="l8wecjb5u"/></g><defs><radialGradient id="ik5rUnb" cx="0" cy="0" r="1" gradientTransform="rotate(137.364 9.222 8.456)scale(19.2851 18.0913)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="fslrr3bpx"/></radialGradient><radialGradient id="iVPV2ye" cx="0" cy="0" r="1" gradientTransform="rotate(-52.485 36.14 5.15)scale(12.2133 19.289)" gradientUnits="userSpaceOnUse"><stop class="uhvuzx_ui"/><stop offset="1" class="w3__hzb0z"/></radialGradient><radialGradient id="ik9LpPe" cx="0" cy="0" r="1" gradientTransform="matrix(6.9375 5.625 -5.88867 7.2627 7.61 7.18)" gradientUnits="userSpaceOnUse"><stop class="onyixvbsj"/><stop offset="1" class="mwd8avblo"/></radialGradient><radialGradient id="iRPqlxb" cx="0" cy="0" r="1" gradientTransform="matrix(1.20311 -1.39063 4.2248 3.65513 6.922 20.4)" gradientUnits="userSpaceOnUse"><stop class="zc1e6_uqb"/><stop offset="1" class="i951vmqly"/></radialGradient><radialGradient id="i0mrpcc" cx="0" cy="0" r="1" gradientTransform="matrix(.40625 -1.5995 8.05286 2.04532 7.797 18.43)" gradientUnits="userSpaceOnUse"><stop offset=".103" class="zc1e6_uqb"/><stop offset="1" class="qz913sb2z"/></radialGradient><radialGradient id="it61IRc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.1158 -2.1416 .40653 -1.16093 23.944 24.357)" gradientUnits="userSpaceOnUse"><stop class="dexldfx8f"/><stop offset="1" class="fxjlaqhak"/></radialGradient><radialGradient id="iQGq3nb" cx="0" cy="0" r="1" gradientTransform="rotate(129.611 12.409 9.097)scale(3.52904 3.95)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="t0o0elbde"/></radialGradient><radialGradient id="immogNd" cx="0" cy="0" r="1" gradientTransform="matrix(2.57813 -2.59374 2.39423 2.37981 24.078 10.587)" gradientUnits="userSpaceOnUse"><stop class="omvgj2mkb"/><stop offset="1" class="nt-tsgc9h"/></radialGradient><radialGradient id="iUmMFmb" cx="0" cy="0" r="1" gradientTransform="matrix(5.56252 3.71872 -2.84673 4.25818 22.047 3.65)" gradientUnits="userSpaceOnUse"><stop offset=".042" class="w8tzhgbne"/><stop offset=".885" class="ho6bpr2uf"/></radialGradient><radialGradient id="il9cZje" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68634 2.21885 -2.48353 -1.8875 22.311 3.79)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="t0o0elbde"/></radialGradient><radialGradient id="iXrWZwe" cx="0" cy="0" r="1" gradientTransform="matrix(1.46444 -1.47332 1.35999 1.3518 20.465 6.772)" gradientUnits="userSpaceOnUse"><stop class="omvgj2mkb"/><stop offset="1" class="nt-tsgc9h"/></radialGradient><radialGradient id="iqOO73c" cx="0" cy="0" r="1" gradientTransform="matrix(3.51669 2.03677 -1.3194 2.27806 19.311 2.831)" gradientUnits="userSpaceOnUse"><stop offset=".042" class="w8tzhgbne"/><stop offset=".885" class="ho6bpr2uf"/></radialGradient><radialGradient id="iwjsO4c" cx="0" cy="0" r="1" gradientTransform="rotate(124.086 4.596 19.658)scale(2.50921 3.81653)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="dexldfx8f"/></radialGradient><radialGradient id="iEwzYup" cx="0" cy="0" r="1" gradientTransform="matrix(1.60937 1.21875 -.93297 1.232 21.281 26.68)" gradientUnits="userSpaceOnUse"><stop offset=".042" class="p182jkbza"/><stop offset=".885" class="cdfyphj2d"/></radialGradient><radialGradient id="iv7onwb" cx="0" cy="0" r="1" gradientTransform="rotate(-37.826 25.678 -10.133)scale(12.7393 9.72104)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="cccuqobup"/><stop offset="1" class="srx97_6cz"/></radialGradient><radialGradient id="icgocRb" cx="0" cy="0" r="1" gradientTransform="matrix(5.90519 -6.74995 5.3936 4.71858 11.204 14.056)" gradientUnits="userSpaceOnUse"><stop class="oe5pg7b5n"/><stop offset="1" class="d4zx8i2ti"/></radialGradient><radialGradient id="ipxD2Ib" cx="0" cy="0" r="1" gradientTransform="matrix(3.03014 -4.0625 3.64702 2.72023 11.204 12.993)" gradientUnits="userSpaceOnUse"><stop class="vu6p_gbvh"/><stop offset="1" class="d4zx8i2ti"/></radialGradient><radialGradient id="iHuE43d" cx="0" cy="0" r="1" gradientTransform="matrix(4.65624 2.28127 -6.83397 13.94864 10.078 20.962)" gradientUnits="userSpaceOnUse"><stop offset=".054" class="ecjww7spy"/><stop offset="1" class="vzsb2ko7n"/></radialGradient><radialGradient id="iQGQlLr" cx="0" cy="0" r="1" gradientTransform="matrix(6.78643 3.62537 -7.90217 14.7923 7.948 19.618)" gradientUnits="userSpaceOnUse"><stop offset=".054" class="ecjww7spy"/><stop offset="1" class="vzsb2ko7n"/></radialGradient><radialGradient id="i4SxLfP" cx="0" cy="0" r="1" gradientTransform="matrix(8.75 3.5 -6.6245 16.56124 14.922 13.556)" gradientUnits="userSpaceOnUse"><stop class="cccuqobup"/><stop offset="1" class="srx97_6cz"/></radialGradient><radialGradient id="iwbeASb" cx="0" cy="0" r="1" gradientTransform="matrix(8.375 0 0 23 9.86 17.056)" gradientUnits="userSpaceOnUse"><stop class="ecjww7spy"/><stop offset="1" class="vzsb2ko7n"/></radialGradient><radialGradient id="isHbAHb" cx="0" cy="0" r="1" gradientTransform="rotate(151.579 12.872 9.807)scale(6.04055 13.7133)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></radialGradient><filter id="idQKgJe" width="12.091" height="12.092" x="9.954" y="4.213" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7145_6142" stdDeviation=".625"/></filter><filter id="i7oKnGd" width="12.503" height="12.503" x="9.609" y="15.685" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7145_6142" stdDeviation=".625"/></filter><filter id="ifeAyzc" width="17.127" height="15.909" x="11.984" y="8.045" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7145_6142" stdDeviation=".625"/></filter><filter id="i0FwgVe" width="11.531" height="9.281" x="12.672" y="16.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7145_6142" stdDeviation="1"/></filter><filter id="iANZTwc" width="7.344" height="2.656" x="1.766" y="14.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7145_6142" stdDeviation=".5"/></filter><linearGradient id="iHLJied" x1="4.859" x2="16.609" y1="19.493" y2="19.493" gradientUnits="userSpaceOnUse"><stop class="l_ro060mt"/><stop offset="1" class="n2zztfbhy"/></linearGradient><linearGradient id="iYtMhab" x1="30.297" x2="24.261" y1="28.993" y2="20.244" gradientUnits="userSpaceOnUse"><stop offset=".103" class="zc1e6_uqb"/><stop offset="1" class="qz913sb2z"/></linearGradient><linearGradient id="iTXwjLe" x1="8.797" x2="10.672" y1="7.681" y2="9.368" gradientUnits="userSpaceOnUse"><stop class="m34edbb-k"/><stop offset="1" class="x3vkdwbjx"/></linearGradient><linearGradient id="iMfrNgo" x1="19.672" x2="23.172" y1="26.806" y2="16.931" gradientUnits="userSpaceOnUse"><stop offset=".103" class="zc1e6_uqb"/><stop offset="1" class="qz913sb2z"/></linearGradient><linearGradient id="iuzFwed" x1="19.797" x2="14.641" y1="22.837" y2="19.087" gradientUnits="userSpaceOnUse"><stop class="ytrarrpuv"/><stop offset="1" class="dyr957b_g"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:dashing-away" /></template>
<style>
.cccuqobup {
  stop-color: var(--svg-color--cdc7c7, #CDC7C7);
}

.cdfyphj2d {
  stop-color: var(--svg-color--e5ccef, #E5CCEF);
  stop-opacity: 0;
}

.d4zx8i2ti {
  stop-color: var(--svg-color--beb4e8, #BEB4E8);
  stop-opacity: 0;
}

.dexldfx8f {
  stop-color: var(--svg-color--ada0f1, #ADA0F1);
}

.dh5e3bmbz {
  d: path("M25.335 22.237a7.2 7.2 0 0 1-2.768 1.034a.88.88 0 0 0-.703.605a5.9 5.9 0 0 1-.918 1.766c-1.35-1.2-3.019-2.983-4.555-5.149c.837.517 5.109 1.95 8.944 1.744");
}

.dyr957b_g {
  stop-color: var(--svg-color--aea3e4, #AEA3E4);
  stop-opacity: 0;
}

.ecjww7spy {
  stop-color: var(--svg-color--aea1bc, #AEA1BC);
}

.fslrr3bpx {
  stop-color: var(--svg-color--dcc4e7, #DCC4E7);
}

.ft5dv1b6b {
  fill: none;
}

.fxjlaqhak {
  stop-color: var(--svg-color--ada0f1, #ADA0F1);
  stop-opacity: 0;
}

.ho6bpr2uf {
  stop-color: var(--svg-color--afada8, #AFADA8);
  stop-opacity: 0;
}

.i951vmqly {
  stop-color: var(--svg-color--a998f0, #A998F0);
  stop-opacity: 0;
}

.ibv8g_bhn {
  d: path("M21.852 8.387a.88.88 0 0 0 .703.6a7.224 7.224 0 0 1 .012 14.284a.88.88 0 0 0-.703.605a5.885 5.885 0 0 1-11.261-.162l-.001.002c-.602-2.13-1.557-4.085-4.68-5.356c-.342-.153-.27-.568.1-.515c1.289.182 2.886.697 4.551 1.526c.17.085.363.041.482-.081c.033-.063.057-.056.092-.118l.008-.045l.003-.023a.52.52 0 0 0-.226-.508c-1.256-.774-4.02-1.485-7.83-1.577c-.938 0-1.33-.375-1.352-.838c.022-.464.273-.838 1.352-.838c3.81-.092 6.574-.804 7.83-1.577a.52.52 0 0 0 .226-.508l-.003-.023a.41.41 0 0 0-.592-.314c-1.665.83-3.297 1.317-4.585 1.499c-.371.052-.443-.362-.101-.516c3.522-1.581 4.177-3.608 4.555-4.78q.066-.206.126-.374a5.885 5.885 0 0 1 11.294-.363");
}

.l_ro060mt {
  stop-color: var(--svg-color--c4b5be, #C4B5BE);
}

.l8wecjb5u {
  stroke: var(--svg-color--eee2e3, #EEE2E3);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M2.89 16.056c.949-.021 3.294-.132 5.094-.407");
}

.m34edbb-k {
  stop-color: var(--svg-color--aea3a5, #AEA3A5);
}

.mwd8avblo {
  stop-color: var(--svg-color--b3a8a8, #B3A8A8);
  stop-opacity: 0;
}

.n2zztfbhy {
  stop-color: var(--svg-color--c4b5be, #C4B5BE);
  stop-opacity: 0;
}

.n72quk_el {
  cx: 15.861px;
  cy: 21.936px;
  r: 5.002px;
}

.nt-tsgc9h {
  stop-color: var(--svg-color--fff3c7, #FFF3C7);
  stop-opacity: 0;
}

.oe5pg7b5n {
  stop-color: var(--svg-color--beb4e8, #BEB4E8);
}

.ogtyo31au {
  d: path("M11.133 18.853a2.185 2.185 0 0 0-1.12-3.492l-2.037-.551c-1.324.286-2.968.487-4.874.533c-1.079 0-1.33.374-1.352.838c.022.463.414.838 1.352.838c3.81.092 6.574.803 7.83 1.577c.099.06.166.152.201.257");
}

.omvgj2mkb {
  stop-color: var(--svg-color--fff3c7, #FFF3C7);
}

.onyixvbsj {
  stop-color: var(--svg-color--b3a8a8, #B3A8A8);
}

.p182jkbza {
  stop-color: var(--svg-color--e5ccef, #E5CCEF);
}

.pcr86sbvm {
  stroke-linecap: round;
  d: path("M15.172 18.556c.854.937 2.844 3.375 6.531 4.28");
}

.qv-q-dbaw {
  cx: 21.93px;
  cy: 4.704px;
  r: 1.305px;
}

.qz913sb2z {
  stop-color: var(--svg-color--b6a8f2, #B6A8F2);
  stop-opacity: 0;
}

.srx97_6cz {
  stop-color: var(--svg-color--cdc7c7, #CDC7C7);
  stop-opacity: 0;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t0o0elbde {
  stop-color: var(--svg-color--ded0e4, #DED0E4);
}

.uhvuzx_ui {
  stop-color: var(--svg-color--9b91f1, #9B91F1);
}

.uz03lkm3d {
  cx: 16px;
  cy: 10.259px;
  r: 4.796px;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vu6p_gbvh {
  stop-color: var(--svg-color--a99dca, #A99DCA);
}

.vzsb2ko7n {
  stop-color: var(--svg-color--aea1bc, #AEA1BC);
  stop-opacity: 0;
}

.w3__hzb0z {
  stop-color: var(--svg-color--9b91f1, #9B91F1);
  stop-opacity: 0;
}

.w8tzhgbne {
  stop-color: var(--svg-color--afada8, #AFADA8);
}

.x3vkdwbjx {
  stop-color: var(--svg-color--aea3a5, #AEA3A5);
  stop-opacity: 0;
}

.yg15wcy7d {
  cx: 22.57px;
  cy: 27.657px;
  r: 1.289px;
}

.yqacpthxm {
  d: path("M27.813 15.939c.421 2.867-1.9 6.477-5.883 6.742c-5.164.343-8.696-3.047-8.696-6.742c0-3.696 4.25-7.196 8.696-6.57c3.249 0 5.883 3.32 5.883 6.57");
}

.ytrarrpuv {
  stop-color: var(--svg-color--aea3e4, #AEA3E4);
}

.z_9vl-bwa {
  cx: 26.656px;
  cy: 6.946px;
  r: 2.297px;
}

.zc1e6_uqb {
  stop-color: var(--svg-color--b6a8f2, #B6A8F2);
}

</style>
