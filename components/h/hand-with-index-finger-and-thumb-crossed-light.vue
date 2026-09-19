<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ii129Hc)"><path fill="url(#ierAAHe)" class="df7civnnb"/><path fill="url(#iimqEXb)" class="df7civnnb"/><path fill="url(#iOmxfVd)" class="df7civnnb"/></g><g filter="url(#ihnyLPM)"><path fill="url(#il060ac)" class="iqnxj09js"/></g><g filter="url(#iYhbAgd)"><rect fill="url(#iiZ9Z7c)" transform="rotate(30 16.28 2.357)" class="xf4gk_b5d"/><rect fill="url(#iFYILrc)" transform="rotate(30 16.28 2.357)" class="xf4gk_b5d"/></g><g filter="url(#iXq6FSc)"><rect fill="url(#iZVnz4d)" transform="rotate(32.721 17.43 9.96)" class="j3bxhebqk"/><rect fill="url(#i0y1VVb)" transform="rotate(32.721 17.43 9.96)" class="j3bxhebqk"/></g><g filter="url(#ib9v1ed)"><rect fill="url(#iYfCZQb)" transform="rotate(32.721 20.905 13.32)" class="l3bs9_bge"/><rect fill="url(#i4LZXPU)" transform="rotate(32.721 20.905 13.32)" class="l3bs9_bge"/></g><g filter="url(#iBBMEib)"><rect fill="url(#iZua8ce)" transform="rotate(34.472 23.665 16.927)" class="t5crtj5dm"/><rect fill="url(#iSJxF1b)" transform="rotate(34.472 23.665 16.927)" class="t5crtj5dm"/></g><g filter="url(#iT13HDd)"><ellipse transform="rotate(36.17 14.863 12.839)" class="t4-ox_htq"/><path class="kr_tiozya"/></g><g filter="url(#iksY5Xd)"><ellipse transform="rotate(36.17 18.816 16)" class="kswd_qncx"/><path class="nj9o2xxim"/></g><g filter="url(#i4J71Cd)"><ellipse transform="rotate(36.17 21.83 18.986)" class="rmpkx-buq"/><path class="rciqj532d"/></g><defs><filter id="ii129Hc" width="6.149" height="8.616" x="8.204" y="1.997" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.768627 0 0 0 0 0.670588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2437"/></filter><filter id="ihnyLPM" width="22.325" height="28.931" x="4.713" y="1.598" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.784314 0 0 0 0 0.694118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2437"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.545098 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_2437" result="effect2_innerShadow_20020_2437"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.839216 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_20020_2437" result="effect3_innerShadow_20020_2437"/></filter><filter id="iYhbAgd" width="13.056" height="17.785" x="7.181" y="1.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2437" stdDeviation=".75"/></filter><filter id="iXq6FSc" width="10.27" height="12.135" x="11.207" y="9.207" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2437" stdDeviation=".75"/></filter><filter id="ib9v1ed" width="10.45" height="12.415" x="14.503" y="12.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2437" stdDeviation=".75"/></filter><filter id="iBBMEib" width="10.445" height="12.056" x="17.185" y="16.191" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2437" stdDeviation=".75"/></filter><filter id="iT13HDd" width="4.824" height="5.998" x="12.451" y="9.84" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2437" stdDeviation=".2"/></filter><filter id="iksY5Xd" width="4.148" height="5.069" x="16.742" y="13.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2437" stdDeviation=".2"/></filter><filter id="i4J71Cd" width="3.659" height="4.396" x="20.001" y="16.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2437" stdDeviation=".2"/></filter><radialGradient id="ierAAHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.94364 4.44518 -4.2145 -.89467 12.147 3.283)" gradientUnits="userSpaceOnUse"><stop class="v-_zx_bok"/><stop offset="1" class="cpjyln0dr"/></radialGradient><radialGradient id="iimqEXb" cx="0" cy="0" r="1" gradientTransform="rotate(-104.25 9.22 -1.49)scale(3.00976 1.77464)" gradientUnits="userSpaceOnUse"><stop offset=".209" class="bdl2v5bjq"/><stop offset="1" class="y1k79l9wt"/></radialGradient><radialGradient id="iOmxfVd" cx="0" cy="0" r="1" gradientTransform="matrix(.59053 2.00963 -2.74222 .8058 9.18 2.147)" gradientUnits="userSpaceOnUse"><stop class="f0cqa2bho"/><stop offset="1" class="nyqjjg7jb"/></radialGradient><radialGradient id="il060ac" cx="0" cy="0" r="1" gradientTransform="rotate(90.82 5.72 10.838)scale(22.645 22.0007)" gradientUnits="userSpaceOnUse"><stop class="tk973up8n"/><stop offset="1" class="n0uah9ban"/></radialGradient><radialGradient id="iFYILrc" cx="0" cy="0" r="1" gradientTransform="matrix(1.44964 -2.10905 1.82442 1.254 18.869 3.441)" gradientUnits="userSpaceOnUse"><stop offset=".224" class="zfgsai7gf"/><stop offset="1" class="rb9ypvr6g"/></radialGradient><radialGradient id="i0y1VVb" cx="0" cy="0" r="1" gradientTransform="matrix(-.31566 4.67938 -2.19689 -.1482 20.415 10.587)" gradientUnits="userSpaceOnUse"><stop offset=".224" class="zpfp7ccna"/><stop offset="1" class="evyv31bdl"/></radialGradient><radialGradient id="i4LZXPU" cx="0" cy="0" r="1" gradientTransform="matrix(-.31566 4.83338 -2.1975 -.14352 23.89 13.968)" gradientUnits="userSpaceOnUse"><stop offset=".224" class="zpfp7ccna"/><stop offset="1" class="evyv31bdl"/></radialGradient><radialGradient id="iSJxF1b" cx="0" cy="0" r="1" gradientTransform="matrix(-.31567 4.69397 -2.19695 -.14774 26.65 17.557)" gradientUnits="userSpaceOnUse"><stop offset=".224" class="zpfp7ccna"/><stop offset="1" class="evyv31bdl"/></radialGradient><linearGradient id="iiZ9Z7c" x1="18.249" x2="17.562" y1="6.994" y2="17.826" gradientUnits="userSpaceOnUse"><stop class="o2m-2stzb"/><stop offset="1" class="kp3b2yctt"/></linearGradient><linearGradient id="iZVnz4d" x1="19.573" x2="19.336" y1="12.801" y2="19.456" gradientUnits="userSpaceOnUse"><stop class="rxvy41oub"/><stop offset="1" class="pn3lhfbzl"/></linearGradient><linearGradient id="iYfCZQb" x1="23.048" x2="22.795" y1="16.255" y2="23.128" gradientUnits="userSpaceOnUse"><stop class="rxvy41oub"/><stop offset="1" class="pn3lhfbzl"/></linearGradient><linearGradient id="iZua8ce" x1="25.809" x2="25.57" y1="19.777" y2="26.452" gradientUnits="userSpaceOnUse"><stop class="rxvy41oub"/><stop offset="1" class="pn3lhfbzl"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hand-with-index-finger-and-thumb-crossed-light" /></template>
<style>
.bdl2v5bjq {
  stop-color: var(--svg-color--e1a483, #E1A483);
}

.cpjyln0dr {
  stop-color: var(--svg-color--fbc1aa, #FBC1AA);
}

.df7civnnb {
  d: path("M9.586 7.52c.4 1.075.75 2.531.797 3.094l3.82-5.578c-.875-1.922-2.085-2.746-3.164-2.868c-1.25-.14-2.398.422-2.797 1.766c-.258 1.383.844 2.242 1.344 3.586");
}

.evyv31bdl {
  stop-color: var(--svg-color--ffe8cb, #FFE8CB);
  stop-opacity: 0;
}

.f0cqa2bho {
  stop-color: var(--svg-color--cc9c7a, #CC9C7A);
}

.ft5dv1b6b {
  fill: none;
}

.iqnxj09js {
  d: path("M14.422 3.52c.783-1.29 2.514-1.844 3.803-1.061s1.7 2.462.918 3.752L16.89 9.92a2.788 2.788 0 0 1 3.69 3.197a2.842 2.842 0 0 1 3.234 3.46a2.8 2.8 0 0 1 1.642.521c1.313.813 1.75 2.89.874 4.459l-2.963 4.33l-.024.037c-4.379 6.767-11.875 4.263-16.309-.982c-3-3.975-1.656-7.219-.484-9.04l4.41-6.741z");
}

.j3bxhebqk {
  width: 3.917px;
  height: 10.119px;
  x: 17.429px;
  y: 9.959px;
  rx: 1.958px;
}

.kp3b2yctt {
  stop-color: var(--svg-color--fcc0b4, #FCC0B4);
  stop-opacity: 0;
}

.kr_tiozya {
  stroke: var(--svg-color--f2ac9b, #F2AC9B);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.14 15.197c.092.068.19.033.212.025a.4.4 0 0 0 .085-.048q.066-.05.144-.129a7 7 0 0 0 .402-.45c.32-.383.74-.924 1.185-1.533a31 31 0 0 0 1.101-1.594c.133-.21.24-.388.307-.52q.052-.098.079-.176a.4.4 0 0 0 .02-.096a.22.22 0 0 0-.088-.195a.22.22 0 0 0-.213-.024a.4.4 0 0 0-.085.047a1.3 1.3 0 0 0-.144.129a7 7 0 0 0-.402.45c-.32.383-.74.924-1.186 1.533a31 31 0 0 0-1.1 1.594c-.133.21-.24.388-.307.52a1.3 1.3 0 0 0-.079.176a.4.4 0 0 0-.02.096a.22.22 0 0 0 .088.195Z");
}

.kswd_qncx {
  cx: 18.816px;
  cy: 16px;
  fill: var(--svg-color--f8ad8f, #F8AD8F);
  rx: 0.178px;
  ry: 2.145px;
}

.l3bs9_bge {
  width: 3.917px;
  height: 10.452px;
  x: 20.905px;
  y: 13.32px;
  rx: 1.958px;
}

.n0uah9ban {
  stop-color: var(--svg-color--e7acac, #E7ACAC);
}

.nj9o2xxim {
  stroke: var(--svg-color--ffbea4, #FFBEA4);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M17.433 17.893a.22.22 0 0 0 .189.034a.3.3 0 0 0 .088-.04a1 1 0 0 0 .132-.104c.09-.082.203-.204.332-.353c.26-.3.596-.726.948-1.207c.351-.48.655-.93.862-1.268a5 5 0 0 0 .236-.425a1 1 0 0 0 .06-.156a.3.3 0 0 0 .01-.097a.22.22 0 0 0-.09-.17a.22.22 0 0 0-.19-.034a.3.3 0 0 0-.088.04a1 1 0 0 0-.131.104c-.09.082-.204.204-.333.353c-.26.3-.595.726-.947 1.207c-.352.48-.656.93-.862 1.269a5 5 0 0 0-.236.424a1 1 0 0 0-.06.156a.3.3 0 0 0-.01.096a.22.22 0 0 0 .09.17Z");
}

.nyqjjg7jb {
  stop-color: var(--svg-color--fac5aa, #FAC5AA);
  stop-opacity: 0;
}

.o2m-2stzb {
  stop-color: var(--svg-color--fcc0b4, #FCC0B4);
}

.pn3lhfbzl {
  stop-color: var(--svg-color--ffc1b3, #FFC1B3);
  stop-opacity: 0;
}

.rb9ypvr6g {
  stop-color: var(--svg-color--ffe6ca, #FFE6CA);
  stop-opacity: 0;
}

.rciqj532d {
  stroke: var(--svg-color--ffbea4, #FFBEA4);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M20.693 20.542a.23.23 0 0 0 .167.04a.3.3 0 0 0 .091-.03a.7.7 0 0 0 .125-.087c.079-.067.176-.166.284-.285c.216-.24.491-.582.775-.97c.285-.39.527-.755.69-1.034a3 3 0 0 0 .185-.357a.7.7 0 0 0 .045-.145a.3.3 0 0 0 .001-.096a.23.23 0 0 0-.089-.147a.23.23 0 0 0-.167-.04a.3.3 0 0 0-.091.03a.7.7 0 0 0-.125.087a3 3 0 0 0-.284.284c-.216.24-.491.582-.775.97c-.285.39-.527.756-.69 1.035c-.081.138-.146.26-.185.356a.7.7 0 0 0-.045.145a.3.3 0 0 0-.001.097a.22.22 0 0 0 .089.147Z");
}

.rmpkx-buq {
  cx: 21.83px;
  cy: 18.986px;
  fill: var(--svg-color--f8ad8f, #F8AD8F);
  rx: 0.178px;
  ry: 1.727px;
}

.rxvy41oub {
  stop-color: var(--svg-color--ffc1b3, #FFC1B3);
}

.t4-ox_htq {
  cx: 14.863px;
  cy: 12.839px;
  fill: var(--svg-color--da8f72, #DA8F72);
  rx: 0.178px;
  ry: 2.721px;
}

.t5crtj5dm {
  width: 3.917px;
  height: 10.15px;
  x: 23.665px;
  y: 16.927px;
  rx: 1.958px;
}

.tk973up8n {
  stop-color: var(--svg-color--ffceaf, #FFCEAF);
}

.v-_zx_bok {
  stop-color: var(--svg-color--ffdbbc, #FFDBBC);
}

.xf4gk_b5d {
  width: 3.597px;
  height: 16.515px;
  x: 16.28px;
  y: 2.357px;
  rx: 1.799px;
}

.y1k79l9wt {
  stop-color: var(--svg-color--f6bba2, #F6BBA2);
  stop-opacity: 0;
}

.zfgsai7gf {
  stop-color: var(--svg-color--ffe6ca, #FFE6CA);
}

.zpfp7ccna {
  stop-color: var(--svg-color--ffe8cb, #FFE8CB);
}

</style>
