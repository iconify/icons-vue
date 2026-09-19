<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iovMPMb)"><path fill="url(#i5wEinb)" class="psx10hb_y"/><path fill="url(#iicszae)" class="psx10hb_y"/><path fill="url(#iX6T7Oc)" class="psx10hb_y"/><path fill="url(#iMhjqQd)" class="psx10hb_y"/><path fill="url(#itICnbd)" class="psx10hb_y"/><path fill="url(#iwyqOSb)" class="psx10hb_y"/></g><path fill="url(#iurZBTc)" class="vlmmw3b4b"/><path fill="url(#i3vanfb)" class="vlmmw3b4b"/><g filter="url(#iRMwgrX)"><rect fill="url(#iXaIe6b)" class="r4e1i-c9p"/></g><g filter="url(#i5R7vdb)"><rect fill="url(#iyQn3Mb)" transform="rotate(-51.165 22.317 12.946)" class="yri2ekbvr"/></g><g filter="url(#ikLA1Ku)"><rect class="q3nurjber"/></g><g filter="url(#inpXvCd)"><rect class="zmpfi5blm"/></g><g filter="url(#i1GTfub)"><rect class="hp8768blc"/></g><defs><filter id="iovMPMb" width="26.537" height="28.714" x="3.801" y="1.268" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.231373 0 0 0 0 0.145098 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5437"/></filter><filter id="iRMwgrX" width="4.47" height="15.258" x="18.779" y="14.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5437" stdDeviation=".75"/></filter><filter id="i5R7vdb" width="8.571" height="7.842" x="21.188" y="10.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5437" stdDeviation=".75"/></filter><filter id="ikLA1Ku" width="3.788" height="5.164" x="5.149" y="16.968" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5437" stdDeviation=".5"/></filter><filter id="inpXvCd" width="3.788" height="5.164" x="9.791" y="17.965" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5437" stdDeviation=".5"/></filter><filter id="i1GTfub" width="3.788" height="5.164" x="14.106" y="18.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5437" stdDeviation=".5"/></filter><radialGradient id="i5wEinb" cx="0" cy="0" r="1" gradientTransform="matrix(-12.546 15.2168 -22.41995 -18.48486 21.64 7.53)" gradientUnits="userSpaceOnUse"><stop class="nq7i09z9i"/><stop offset="1" class="pxzodtb2t"/><stop offset="1" class="pxzodtb2t"/></radialGradient><radialGradient id="iX6T7Oc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.903 5.2104 -12.28143 -11.55686 24.7 8.575)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="sbx8fcbzs"/><stop offset="1" class="yg_bllb4u"/></radialGradient><radialGradient id="iMhjqQd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.19151 2.37896 0 8.08 22.57)" gradientUnits="userSpaceOnUse"><stop class="jh76v7v_w"/><stop offset="1" class="gch_uvicx"/></radialGradient><radialGradient id="itICnbd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.94495 2.95871 0 12.724 23.598)" gradientUnits="userSpaceOnUse"><stop class="jh76v7v_w"/><stop offset="1" class="gch_uvicx"/></radialGradient><radialGradient id="iwyqOSb" cx="0" cy="0" r="1" gradientTransform="rotate(-145.033 17.605 5.661)scale(9.7783 4.57856)" gradientUnits="userSpaceOnUse"><stop class="iw2uoe2-j"/><stop offset="1" class="f-6ffm6lr"/></radialGradient><linearGradient id="iicszae" x1="1.587" x2="22.874" y1="14.105" y2="14.105" gradientUnits="userSpaceOnUse"><stop class="rk9yz2b8g"/><stop offset=".293" class="mleb6mb5e"/></linearGradient><linearGradient id="iurZBTc" x1="16.657" x2="19.98" y1="24.54" y2="24.54" gradientUnits="userSpaceOnUse"><stop class="lbkqp-l-i"/><stop offset="1" class="s8buw3bav"/></linearGradient><linearGradient id="i3vanfb" x1="19.025" x2="19.025" y1="19.49" y2="22.55" gradientUnits="userSpaceOnUse"><stop class="jo9nph1cu"/><stop offset="1" class="rfz2yfljl"/></linearGradient><linearGradient id="iXaIe6b" x1="21.014" x2="21.014" y1="12.667" y2="28.258" gradientUnits="userSpaceOnUse"><stop class="vsq1etvgt"/><stop offset="1" class="deta1t3nu"/></linearGradient><linearGradient id="iyQn3Mb" x1="23.231" x2="23.231" y1="11.142" y2="19.579" gradientUnits="userSpaceOnUse"><stop class="cv7wwgeqb"/><stop offset="1" class="l_3w1myze"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:backhand-index-pointing-down-dark" /></template>
<style>
.cv7wwgeqb {
  stop-color: var(--svg-color--665250, #665250);
  stop-opacity: 0;
}

.deta1t3nu {
  stop-color: var(--svg-color--5f4747, #5F4747);
}

.f-6ffm6lr {
  stop-color: var(--svg-color--361d31, #361D31);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gch_uvicx {
  stop-color: var(--svg-color--382136, #382136);
  stop-opacity: 0;
}

.hp8768blc {
  width: 1.788px;
  height: 3.164px;
  x: 15.106px;
  y: 19.91px;
  fill: var(--svg-color--553c41, #553C41);
  rx: 0.894px;
}

.iw2uoe2-j {
  stop-color: var(--svg-color--361d31, #361D31);
}

.jh76v7v_w {
  stop-color: var(--svg-color--382136, #382136);
}

.jo9nph1cu {
  stop-color: var(--svg-color--503438, #503438);
}

.l_3w1myze {
  stop-color: var(--svg-color--665250, #665250);
}

.lbkqp-l-i {
  stop-color: var(--svg-color--3e282a, #3E282A);
}

.mleb6mb5e {
  stop-color: var(--svg-color--3f2a28, #3F2A28);
  stop-opacity: 0;
}

.nq7i09z9i {
  stop-color: var(--svg-color--5f4845, #5F4845);
}

.psx10hb_y {
  d: path("M28.042 13.88c1.24.86 1.702 2.597.888 3.849a2.657 2.657 0 0 1-3.702.781l-2.61-1.695v10.53a2.637 2.637 0 1 1-5.274 0v-4.284a2.494 2.494 0 0 1-4.564-.344a2.724 2.724 0 0 1-4.487-.884a2.723 2.723 0 0 1-4.493-2.07v-3.102l.002-.104v-4.859c0-1.431.849-3.878 2.51-6.022q.25-.33.527-.637l.01-.013a9.2 9.2 0 0 1 6.833-3.008a9.2 9.2 0 0 1 7.577 3.945c.603.832.892 1.506 1.178 2.175c.22.513.438 1.023.797 1.601c.566.913 1.4 1.59 1.865 1.969l.098.08h-.002z");
}

.pxzodtb2t {
  stop-color: var(--svg-color--44242e, #44242E);
}

.q3nurjber {
  width: 1.788px;
  height: 3.164px;
  x: 6.149px;
  y: 17.968px;
  fill: var(--svg-color--553c41, #553C41);
  rx: 0.894px;
}

.r4e1i-c9p {
  width: 1.47px;
  height: 12.258px;
  x: 20.279px;
  y: 16px;
  rx: 0.735px;
}

.rfz2yfljl {
  stop-color: var(--svg-color--503438, #503438);
  stop-opacity: 0;
}

.rk9yz2b8g {
  stop-color: var(--svg-color--3f2a28, #3F2A28);
}

.s8buw3bav {
  stop-color: var(--svg-color--3e282a, #3E282A);
  stop-opacity: 0;
}

.sbx8fcbzs {
  stop-color: var(--svg-color--685250, #685250);
}

.vlmmw3b4b {
  d: path("M17.344 19.49v7.855a2.637 2.637 0 1 0 5.273 0V19.49z");
}

.vsq1etvgt {
  stop-color: var(--svg-color--5f4747, #5F4747);
  stop-opacity: 0;
}

.yg_bllb4u {
  stop-color: var(--svg-color--685250, #685250);
  stop-opacity: 0;
}

.yri2ekbvr {
  width: 1.828px;
  height: 6.633px;
  x: 22.317px;
  y: 12.946px;
  rx: 0.914px;
}

.zmpfi5blm {
  width: 1.788px;
  height: 3.164px;
  x: 10.791px;
  y: 18.965px;
  fill: var(--svg-color--553c41, #553C41);
  rx: 0.894px;
}

</style>
