<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#iakKZsb)" class="iqdq745cv"/><path fill="url(#ihfvb6c)" class="iqdq745cv"/><path fill="url(#iAhhSNd)" class="iqdq745cv"/><g filter="url(#iClF79B)"><ellipse transform="rotate(-43.715 22.352 9.9)" class="usn607q-m"/></g><g filter="url(#iLPR1be)"><ellipse transform="scale(-1 1)rotate(-34.603 12.346 14.426)" class="qm2hjsk2s"/></g><g filter="url(#iOhcQrd)"><path class="bmno7kt8x"/></g><g filter="url(#iWI1iFa)"><path class="dfb7d-bop"/></g><path fill="url(#iivqkle)" class="hgya-lkwf"/><path fill="url(#igE2HQd)" class="hgya-lkwf"/><path fill="url(#iOExUWc)" class="hgya-lkwf"/><path fill="url(#iqkLnMz)" class="s9lwksjcs"/><path fill="url(#i8ZjDje)" class="s9lwksjcs"/><path fill="url(#i7pvwQe)" class="s9lwksjcs"/><path fill="url(#icH6akc)" class="s9lwksjcs"/><g filter="url(#iGe4kqj)"><path class="vpvz3_n4j"/></g><path fill="url(#idWfM2c)" class="jgt1wabfp"/><g filter="url(#ikrx0Ne)"><path class="fm_1tfgok"/></g><path fill="url(#iyuNine)" class="otnileb3g"/><path stroke="url(#iVsibeb)" class="j3-7z9btb"/></g><defs><radialGradient id="iakKZsb" cx="0" cy="0" r="1" gradientTransform="rotate(-124.672 19.611 8.284)scale(29.3341 85.8278)" gradientUnits="userSpaceOnUse"><stop offset=".393" class="cz2_3bblj"/><stop offset="1" class="cueboovgi"/><stop offset="1" class="fsdljum4g"/></radialGradient><radialGradient id="ihfvb6c" cx="0" cy="0" r="1" gradientTransform="rotate(-153.522 10.917 6.831)scale(18.5035 22.2682)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="vk947wa_z"/><stop offset="1" class="i8rglcb5w"/></radialGradient><radialGradient id="iAhhSNd" cx="0" cy="0" r="1" gradientTransform="rotate(-137.076 12.323 5.438)scale(20.7407 20.4878)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="nkf64-b0r"/><stop offset="1" class="op7do2n0l"/></radialGradient><radialGradient id="iivqkle" cx="0" cy="0" r="1" gradientTransform="matrix(-3.32202 -11.22286 13.92707 -4.12248 12.145 25.118)" gradientUnits="userSpaceOnUse"><stop class="ccr58nbuz"/><stop offset=".234" class="g52oomb1d"/><stop offset="1" class="s79vi8hng"/></radialGradient><radialGradient id="igE2HQd" cx="0" cy="0" r="1" gradientTransform="rotate(-142.786 8.606 7.088)scale(11.105 7.13314)" gradientUnits="userSpaceOnUse"><stop offset=".531" class="pcba2sblg"/><stop offset=".979" class="hk9_ppnyg"/></radialGradient><radialGradient id="iOExUWc" cx="0" cy="0" r="1" gradientTransform="rotate(-153.486 10.88 8.338)scale(15.5407 11.8197)" gradientUnits="userSpaceOnUse"><stop offset=".858" class="xjdrxwzbg"/><stop offset="1" class="ddsy3g_-r"/></radialGradient><radialGradient id="iqkLnMz" cx="0" cy="0" r="1" gradientTransform="matrix(-3.32076 -11.22292 13.923 -4.11969 24.846 25.118)" gradientUnits="userSpaceOnUse"><stop class="ccr58nbuz"/><stop offset=".234" class="g52oomb1d"/><stop offset="1" class="s79vi8hng"/></radialGradient><radialGradient id="i8ZjDje" cx="0" cy="0" r="1" gradientTransform="matrix(-6.93745 -5.9663 5.129 -5.96387 23.642 17.188)" gradientUnits="userSpaceOnUse"><stop offset=".495" class="pcba2sblg"/><stop offset=".979" class="hk9_ppnyg"/></radialGradient><radialGradient id="i7pvwQe" cx="0" cy="0" r="1" gradientTransform="rotate(22.793 -24.171 49.768)scale(12.7453 20.3749)" gradientUnits="userSpaceOnUse"><stop offset=".713" class="pcba2sblg"/><stop offset=".979" class="hk9_ppnyg"/></radialGradient><radialGradient id="icH6akc" cx="0" cy="0" r="1" gradientTransform="rotate(-153.478 17.23 6.841)scale(15.5363 11.8189)" gradientUnits="userSpaceOnUse"><stop offset=".858" class="xjdrxwzbg"/><stop offset="1" class="ddsy3g_-r"/></radialGradient><radialGradient id="iVsibeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.3438 -9.83652 0 16.174 22.313)" gradientUnits="userSpaceOnUse"><stop offset=".07" class="m8pwa1xcy"/><stop offset=".297" class="lwri579ja"/><stop offset=".438" class="gw349qs5e"/></radialGradient><filter id="iClF79B" width="17.627" height="17.796" x="13.539" y="1.003" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6888_5229" stdDeviation="2"/></filter><filter id="iLPR1be" width="10.054" height="11.479" x=".981" y="3.824" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6888_5229" stdDeviation="1.5"/></filter><filter id="iOhcQrd" width="19.555" height="19.824" x="-1.088" y="6.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6888_5229" stdDeviation="2"/></filter><filter id="iWI1iFa" width="17.234" height="18.15" x="12.784" y="8.423" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6888_5229" stdDeviation="2"/></filter><filter id="iGe4kqj" width="5" height="7.125" x="23.65" y="11.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6888_5229" stdDeviation=".75"/></filter><filter id="ikrx0Ne" width="4.308" height="8.403" x="10.861" y="12.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6888_5229" stdDeviation=".75"/></filter><linearGradient id="idWfM2c" x1="24.57" x2="24.482" y1="12.054" y2="16" gradientUnits="userSpaceOnUse"><stop offset=".198" class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iyuNine" x1="11.29" x2="11.202" y1="12.054" y2="16" gradientUnits="userSpaceOnUse"><stop offset=".198" class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:alien" /></template>
<style>
.bmno7kt8x {
  fill: var(--svg-color--608d6a, #608D6A);
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("M12.73 21.194c-2.315 2.382-5.326 1.429-7.652-.964s-3.076-5.297-.76-7.69a5.824 5.824 0 0 1 8.402 0c2.316 2.382 2.337 6.272.01 8.654");
}

.ccr58nbuz {
  stop-color: var(--svg-color--482641, #482641);
}

.cueboovgi {
  stop-color: var(--svg-color--4af492, #4AF492);
}

.cz2_3bblj {
  stop-color: var(--svg-color--92e65b, #92E65B);
}

.ddsy3g_-r {
  stop-color: var(--svg-color--a28d8f, #A28D8F);
}

.dfb7d-bop {
  fill: var(--svg-color--608d6a, #608D6A);
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("M18.17 21.39c1.851 2.044 4.257 1.226 6.117-.829c1.859-2.054 2.457-4.546.607-6.6c-1.85-2.055-4.864-2.045-6.715 0s-1.867 5.384-.008 7.428");
}

.fm_1tfgok {
  stroke: var(--svg-color--686061, #686061);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M12.736 14.344c.442.625.906 2.466.18 4.653");
}

.fsdljum4g {
  stop-color: var(--svg-color--6bd179, #6BD179);
}

.ft5dv1b6b {
  fill: none;
}

.g52oomb1d {
  stop-color: var(--svg-color--4a2943, #4A2943);
}

.gw349qs5e {
  stop-color: var(--svg-color--4b2744, #4B2744);
}

.hgya-lkwf {
  d: path("M13.36 20.78c-2.18 2.18-4.46.92-6.65-1.27s-3.45-4.46-1.27-6.65s5.73-2.18 7.91 0s2.2 5.74.01 7.92");
}

.hk9_ppnyg {
  stop-color: var(--svg-color--1a1819, #1A1819);
}

.i8rglcb5w {
  stop-color: var(--svg-color--67b077, #67B077);
}

.iqdq745cv {
  d: path("M29.92 15.92C29.92 23.61 19 30 16 30S2.08 23.61 2.08 15.92S8.31 2 16 2s13.92 6.23 13.92 13.92");
}

.j3-7z9btb {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-8px, 1.8px);
  d: path("M13.992 25.047s.79.844 2.024.844s1.992-.844 1.992-.844");
}

.jgt1wabfp {
  d: path("M25.67 13.11c.78.78.92 1.9.31 2.51s-1.73.47-2.51-.31s-.92-1.9-.31-2.51s1.74-.46 2.51.31");
}

.lwri579ja {
  stop-color: var(--svg-color--5f4357, #5F4357);
}

.m8pwa1xcy {
  stop-color: var(--svg-color--2e1529, #2E1529);
}

.nkf64-b0r {
  stop-color: var(--svg-color--608d6a, #608D6A);
  stop-opacity: 0;
}

.op7do2n0l {
  stop-color: var(--svg-color--608d6a, #608D6A);
}

.otnileb3g {
  d: path("M12.39 13.11c.78.78.92 1.9.31 2.51s-1.73.47-2.51-.31s-.92-1.9-.31-2.51s1.73-.46 2.51.31");
}

.pcba2sblg {
  stop-color: var(--svg-color--1a1819, #1A1819);
  stop-opacity: 0;
}

.qm2hjsk2s {
  fill: var(--svg-color--baeebc, #BAEEBC);
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  rx: 1.012px;
  ry: 3.253px;
}

.s79vi8hng {
  stop-color: var(--svg-color--654f5f, #654F5F);
}

.s9lwksjcs {
  d: path("M18.64 20.78c2.18 2.18 4.46.92 6.65-1.27s3.45-4.46 1.27-6.65s-5.73-2.18-7.91 0s-2.19 5.74-.01 7.92");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.usn607q-m {
  cx: 22.352px;
  cy: 9.901px;
  fill: var(--svg-color--9efca0, #9EFCA0);
  rx: 3.801px;
  ry: 5.719px;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vk947wa_z {
  stop-color: var(--svg-color--67b077, #67B077);
  stop-opacity: 0;
}

.vpvz3_n4j {
  stroke: var(--svg-color--686061, #686061);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M25.525 13.266c1.633.797 1.469 2.469.625 3.375");
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.xjdrxwzbg {
  stop-color: var(--svg-color--a28d8f, #A28D8F);
  stop-opacity: 0;
}

</style>
