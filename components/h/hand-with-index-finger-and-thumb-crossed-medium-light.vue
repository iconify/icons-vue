<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#irCD3pe)"><path fill="url(#ie2aWqb)" class="uwiagubxt"/><path fill="url(#ieUBw4d)" class="uwiagubxt"/><path fill="url(#iV2XsCE)" class="uwiagubxt"/></g><g filter="url(#iHBpxPe)"><path fill="url(#iDaWpZl)" class="bkzel3u7u"/></g><g filter="url(#iqVmo0d)"><rect fill="url(#iaP1Tae)" transform="rotate(30 16.28 2.297)" class="x8twpnbcv"/><rect fill="url(#irjKZ1e)" transform="rotate(30 16.28 2.297)" class="x8twpnbcv"/></g><g filter="url(#invbeee)"><rect fill="url(#iDYHaib)" transform="rotate(32.721 17.43 9.9)" class="sjef80bfi"/><rect fill="url(#i1PWymg)" transform="rotate(32.721 17.43 9.9)" class="sjef80bfi"/></g><g filter="url(#ibp85kd)"><rect fill="url(#iVfByjd)" transform="rotate(32.721 20.905 13.26)" class="js4jj1bzr"/><rect fill="url(#i1Wh8Yc)" transform="rotate(32.721 20.905 13.26)" class="js4jj1bzr"/></g><g filter="url(#iI08aOb)"><rect fill="url(#in2jbyc)" transform="rotate(34.472 23.665 16.867)" class="ikn0b3-nk"/><rect fill="url(#iaZDSsd)" transform="rotate(34.472 23.665 16.867)" class="ikn0b3-nk"/></g><g filter="url(#ipwv5Oc)"><ellipse transform="rotate(36.17 14.863 12.78)" class="bwf86jb_c"/><path class="mdp8ojjuz"/></g><g filter="url(#i7tfMDd)"><ellipse transform="rotate(36.17 18.816 15.94)" class="vtj5ckvtm"/><path class="r2-y-wify"/></g><g filter="url(#ikHriGe)"><ellipse transform="rotate(36.17 21.83 18.926)" class="cri70kbcy"/><path class="t0ek-e15w"/></g><defs><filter id="irCD3pe" width="6.149" height="8.616" x="8.204" y="1.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.941176 0 0 0 0 0.705882 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2435"/></filter><filter id="iHBpxPe" width="22.325" height="28.931" x="4.713" y="1.539" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.72549 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2435"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.494118 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_2435" result="effect2_innerShadow_20020_2435"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.768627 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_20020_2435" result="effect3_innerShadow_20020_2435"/></filter><filter id="iqVmo0d" width="13.056" height="17.785" x="7.181" y="1.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2435" stdDeviation=".75"/></filter><filter id="invbeee" width="10.27" height="12.135" x="11.207" y="9.147" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2435" stdDeviation=".75"/></filter><filter id="ibp85kd" width="10.45" height="12.415" x="14.503" y="12.508" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2435" stdDeviation=".75"/></filter><filter id="iI08aOb" width="10.445" height="12.056" x="17.185" y="16.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2435" stdDeviation=".75"/></filter><filter id="ipwv5Oc" width="4.824" height="5.998" x="12.451" y="9.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2435" stdDeviation=".2"/></filter><filter id="i7tfMDd" width="4.148" height="5.069" x="16.742" y="13.406" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2435" stdDeviation=".2"/></filter><filter id="ikHriGe" width="3.659" height="4.396" x="20.001" y="16.728" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2435" stdDeviation=".2"/></filter><radialGradient id="ie2aWqb" cx="0" cy="0" r="1" gradientTransform="matrix(-.94364 4.44518 -4.2145 -.89467 12.147 3.223)" gradientUnits="userSpaceOnUse"><stop class="sou82p7od"/><stop offset="1" class="e8p05rbnq"/></radialGradient><radialGradient id="ieUBw4d" cx="0" cy="0" r="1" gradientTransform="rotate(-104.25 9.197 -1.52)scale(3.00976 1.77464)" gradientUnits="userSpaceOnUse"><stop offset=".209" class="v17bdpb9q"/><stop offset="1" class="oh0wnxgfe"/></radialGradient><radialGradient id="iV2XsCE" cx="0" cy="0" r="1" gradientTransform="matrix(.59053 2.00963 -2.74222 .8058 9.18 2.088)" gradientUnits="userSpaceOnUse"><stop class="f0cqa2bho"/><stop offset="1" class="jyq4w1bet"/></radialGradient><radialGradient id="iDaWpZl" cx="0" cy="0" r="1" gradientTransform="rotate(90.82 5.75 10.808)scale(22.645 22.0007)" gradientUnits="userSpaceOnUse"><stop class="etwis3mcu"/><stop offset="1" class="wwv6d8b5n"/></radialGradient><radialGradient id="irjKZ1e" cx="0" cy="0" r="1" gradientTransform="matrix(1.44964 -2.10905 1.82442 1.254 18.869 3.382)" gradientUnits="userSpaceOnUse"><stop offset=".224" class="wzfdw2luh"/><stop offset="1" class="xznyxnbwm"/></radialGradient><radialGradient id="i1PWymg" cx="0" cy="0" r="1" gradientTransform="matrix(-.31566 4.67938 -2.19689 -.1482 20.415 10.528)" gradientUnits="userSpaceOnUse"><stop offset=".224" class="d2at_bbdl"/><stop offset="1" class="bb84-2bwj"/></radialGradient><radialGradient id="i1Wh8Yc" cx="0" cy="0" r="1" gradientTransform="matrix(-.31566 4.83338 -2.1975 -.14352 23.89 13.909)" gradientUnits="userSpaceOnUse"><stop offset=".224" class="d2at_bbdl"/><stop offset="1" class="bb84-2bwj"/></radialGradient><radialGradient id="iaZDSsd" cx="0" cy="0" r="1" gradientTransform="matrix(-.31567 4.69397 -2.19695 -.14774 26.65 17.497)" gradientUnits="userSpaceOnUse"><stop offset=".224" class="d2at_bbdl"/><stop offset="1" class="bb84-2bwj"/></radialGradient><linearGradient id="iaP1Tae" x1="18.249" x2="17.562" y1="6.934" y2="17.766" gradientUnits="userSpaceOnUse"><stop class="r8x_vhaxm"/><stop offset="1" class="qq0ardb2t"/></linearGradient><linearGradient id="iDYHaib" x1="19.573" x2="19.336" y1="12.741" y2="19.396" gradientUnits="userSpaceOnUse"><stop class="hpx1apbae"/><stop offset="1" class="hf15a38fh"/></linearGradient><linearGradient id="iVfByjd" x1="23.048" x2="22.795" y1="16.195" y2="23.068" gradientUnits="userSpaceOnUse"><stop class="hpx1apbae"/><stop offset="1" class="hf15a38fh"/></linearGradient><linearGradient id="in2jbyc" x1="25.809" x2="25.57" y1="19.717" y2="26.392" gradientUnits="userSpaceOnUse"><stop class="hpx1apbae"/><stop offset="1" class="hf15a38fh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hand-with-index-finger-and-thumb-crossed-medium-light" /></template>
<style>
.bb84-2bwj {
  stop-color: var(--svg-color--ffd1ac, #FFD1AC);
  stop-opacity: 0;
}

.bkzel3u7u {
  d: path("M14.422 3.46c.783-1.29 2.514-1.844 3.803-1.061s1.7 2.463.918 3.752L16.89 9.86a2.788 2.788 0 0 1 3.69 3.197a2.842 2.842 0 0 1 3.234 3.46a2.8 2.8 0 0 1 1.642.521c1.313.813 1.75 2.89.874 4.46l-2.963 4.33l-.024.036c-4.379 6.767-11.875 4.263-16.309-.982c-3-3.975-1.656-7.219-.484-9.04l4.41-6.741z");
}

.bwf86jb_c {
  cx: 14.863px;
  cy: 12.779px;
  fill: var(--svg-color--ce8767, #CE8767);
  rx: 0.178px;
  ry: 2.721px;
}

.cri70kbcy {
  cx: 21.83px;
  cy: 18.926px;
  fill: var(--svg-color--dc9370, #DC9370);
  rx: 0.178px;
  ry: 1.727px;
}

.d2at_bbdl {
  stop-color: var(--svg-color--ffd1ac, #FFD1AC);
}

.e8p05rbnq {
  stop-color: var(--svg-color--e0a687, #E0A687);
}

.etwis3mcu {
  stop-color: var(--svg-color--f2bb97, #F2BB97);
}

.f0cqa2bho {
  stop-color: var(--svg-color--cc9c7a, #CC9C7A);
}

.ft5dv1b6b {
  fill: none;
}

.hf15a38fh {
  stop-color: var(--svg-color--e3a49b, #E3A49B);
  stop-opacity: 0;
}

.hpx1apbae {
  stop-color: var(--svg-color--e3a49b, #E3A49B);
}

.ikn0b3-nk {
  width: 3.917px;
  height: 10.15px;
  x: 23.665px;
  y: 16.867px;
  rx: 1.958px;
}

.js4jj1bzr {
  width: 3.917px;
  height: 10.452px;
  x: 20.905px;
  y: 13.26px;
  rx: 1.958px;
}

.jyq4w1bet {
  stop-color: var(--svg-color--e2af88, #E2AF88);
  stop-opacity: 0;
}

.mdp8ojjuz {
  stroke: var(--svg-color--dd9d7e, #DD9D7E);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.14 15.137c.092.068.19.033.212.025a.4.4 0 0 0 .085-.048q.066-.05.144-.129a7 7 0 0 0 .402-.45c.32-.383.74-.924 1.185-1.533a31 31 0 0 0 1.101-1.594c.133-.21.24-.388.307-.52q.052-.098.079-.176a.4.4 0 0 0 .02-.095a.22.22 0 0 0-.088-.196a.22.22 0 0 0-.213-.024a.4.4 0 0 0-.085.048a1.3 1.3 0 0 0-.144.128a7 7 0 0 0-.402.45c-.32.383-.74.924-1.186 1.533a31 31 0 0 0-1.1 1.595c-.133.21-.24.388-.307.52a1.3 1.3 0 0 0-.079.176a.4.4 0 0 0-.02.095a.22.22 0 0 0 .088.195Z");
}

.oh0wnxgfe {
  stop-color: var(--svg-color--e5b08e, #E5B08E);
  stop-opacity: 0;
}

.qq0ardb2t {
  stop-color: var(--svg-color--e9aa9c, #E9AA9C);
  stop-opacity: 0;
}

.r2-y-wify {
  stroke: var(--svg-color--e5a27f, #E5A27F);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M17.433 17.833a.22.22 0 0 0 .189.034a.3.3 0 0 0 .088-.04a1 1 0 0 0 .132-.104c.09-.082.203-.204.332-.353c.26-.3.596-.725.948-1.207c.351-.48.655-.93.862-1.268c.102-.169.184-.314.236-.424a1 1 0 0 0 .06-.157a.3.3 0 0 0 .01-.096a.22.22 0 0 0-.09-.17a.22.22 0 0 0-.19-.034a.3.3 0 0 0-.088.039a1 1 0 0 0-.131.104c-.09.083-.204.205-.333.354c-.26.3-.595.725-.947 1.206s-.656.93-.862 1.269a5 5 0 0 0-.236.424a1 1 0 0 0-.06.157a.3.3 0 0 0-.01.096a.22.22 0 0 0 .09.17Z");
}

.r8x_vhaxm {
  stop-color: var(--svg-color--e9aa9c, #E9AA9C);
}

.sjef80bfi {
  width: 3.917px;
  height: 10.119px;
  x: 17.429px;
  y: 9.9px;
  rx: 1.958px;
}

.sou82p7od {
  stop-color: var(--svg-color--f5c49a, #F5C49A);
}

.t0ek-e15w {
  stroke: var(--svg-color--e5a27f, #E5A27F);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M20.693 20.482a.23.23 0 0 0 .167.04a.3.3 0 0 0 .091-.03a.7.7 0 0 0 .125-.087c.079-.067.176-.165.284-.284c.216-.24.491-.583.775-.971c.285-.389.527-.755.69-1.034a3 3 0 0 0 .185-.357a.7.7 0 0 0 .045-.145a.3.3 0 0 0 .001-.096a.23.23 0 0 0-.089-.147a.23.23 0 0 0-.167-.04a.3.3 0 0 0-.091.03a.7.7 0 0 0-.125.087a3 3 0 0 0-.284.284c-.216.24-.491.582-.775.971s-.527.755-.69 1.034c-.081.138-.146.26-.185.357a.7.7 0 0 0-.045.144a.3.3 0 0 0-.001.097c.006.04.027.102.089.147Z");
}

.uwiagubxt {
  d: path("M9.586 7.46c.4 1.075.75 2.531.797 3.094l3.82-5.578c-.875-1.922-2.085-2.746-3.164-2.867c-1.25-.141-2.398.421-2.797 1.765c-.258 1.383.844 2.242 1.344 3.586");
}

.v17bdpb9q {
  stop-color: var(--svg-color--ca926c, #CA926C);
}

.vtj5ckvtm {
  cx: 18.816px;
  cy: 15.94px;
  fill: var(--svg-color--dc9370, #DC9370);
  rx: 0.178px;
  ry: 2.145px;
}

.wwv6d8b5n {
  stop-color: var(--svg-color--db9997, #DB9997);
}

.wzfdw2luh {
  stop-color: var(--svg-color--ffd0ac, #FFD0AC);
}

.x8twpnbcv {
  width: 3.597px;
  height: 16.515px;
  x: 16.28px;
  y: 2.297px;
  rx: 1.799px;
}

.xznyxnbwm {
  stop-color: var(--svg-color--ffd0ac, #FFD0AC);
  stop-opacity: 0;
}

</style>
