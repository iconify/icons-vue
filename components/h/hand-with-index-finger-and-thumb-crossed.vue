<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iFeh4Pe)"><path fill="url(#idwwxLb)" class="df7civnnb"/><path fill="url(#iFQHE7P)" class="df7civnnb"/></g><g filter="url(#iFd6Tac)"><path fill="url(#irQ6bzc)" class="iqnxj09js"/></g><g filter="url(#ilVPhHh)"><rect fill="url(#iA649Dc)" transform="rotate(30 16.28 2.357)" class="ni69k2b3j"/><rect fill="url(#iGxD7Bd)" transform="rotate(30 16.28 2.357)" class="ni69k2b3j"/></g><g filter="url(#iKdY1eb)"><rect fill="url(#iU1Enkc)" transform="rotate(32.721 17.43 9.96)" class="j3bxhebqk"/><rect fill="url(#iDSuydk)" transform="rotate(32.721 17.43 9.96)" class="j3bxhebqk"/></g><g filter="url(#iKdY1eb)"><rect fill="url(#iU1Enkc)" transform="rotate(32.721 17.43 9.96)" class="j3bxhebqk"/><rect fill="url(#iDSuydk)" transform="rotate(32.721 17.43 9.96)" class="j3bxhebqk"/></g><g filter="url(#itt8FGc)"><rect fill="url(#iYOyyOQ)" transform="rotate(32.721 20.905 13.32)" class="l3bs9_bge"/><rect fill="url(#i9mStdc)" transform="rotate(32.721 20.905 13.32)" class="l3bs9_bge"/></g><g filter="url(#ioItmKI)"><rect fill="url(#iGRQR5d)" transform="rotate(34.472 23.665 16.927)" class="t5crtj5dm"/><rect fill="url(#iZ6dPud)" transform="rotate(34.472 23.665 16.927)" class="t5crtj5dm"/></g><g filter="url(#in3zj7c)"><ellipse transform="rotate(36.17 14.863 12.839)" class="mfs7rhqip"/><path class="jxixykbmj"/></g><g filter="url(#iGD31eq)"><ellipse transform="rotate(36.17 18.816 16)" class="kaucbrclp"/><path class="if18nilxg"/></g><g filter="url(#iVxXnPS)"><ellipse transform="rotate(36.17 21.83 18.986)" class="xp_pabcho"/><path class="wt3q6zy0i"/></g><defs><filter id="iFeh4Pe" width="6.149" height="8.616" x="8.204" y="1.997" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.647059 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2427"/></filter><filter id="iFd6Tac" width="22.325" height="28.931" x="4.713" y="1.598" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.627451 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2427"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.588235 0 0 0 0 0.741176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_2427" result="effect2_innerShadow_20020_2427"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.839216 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_20020_2427" result="effect3_innerShadow_20020_2427"/></filter><filter id="ilVPhHh" width="13.217" height="17.828" x="7.239" y="1.573" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2427" stdDeviation=".75"/></filter><filter id="iKdY1eb" width="10.27" height="12.135" x="11.207" y="9.207" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2427" stdDeviation=".75"/></filter><filter id="itt8FGc" width="10.45" height="12.415" x="14.503" y="12.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2427" stdDeviation=".75"/></filter><filter id="ioItmKI" width="10.445" height="12.056" x="17.185" y="16.191" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2427" stdDeviation=".75"/></filter><filter id="in3zj7c" width="4.824" height="5.998" x="12.451" y="9.84" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2427" stdDeviation=".2"/></filter><filter id="iGD31eq" width="4.148" height="5.069" x="16.742" y="13.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2427" stdDeviation=".2"/></filter><filter id="iVxXnPS" width="3.659" height="4.396" x="20.001" y="16.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2427" stdDeviation=".2"/></filter><radialGradient id="idwwxLb" cx="0" cy="0" r="1" gradientTransform="matrix(-.94364 4.44518 -4.2145 -.89467 12.147 3.283)" gradientUnits="userSpaceOnUse"><stop class="cjthqmk3i"/><stop offset="1" class="wsjlisd8t"/></radialGradient><radialGradient id="iFQHE7P" cx="0" cy="0" r="1" gradientTransform="rotate(-104.25 9.22 -1.49)scale(3.00976 1.77464)" gradientUnits="userSpaceOnUse"><stop offset=".209" class="pmyr8-pev"/><stop offset="1" class="cslhqcceg"/></radialGradient><radialGradient id="irQ6bzc" cx="0" cy="0" r="1" gradientTransform="rotate(90.82 5.72 10.838)scale(22.645 22.0007)" gradientUnits="userSpaceOnUse"><stop class="plaj5ybgu"/><stop offset="1" class="gtxgxst4i"/></radialGradient><radialGradient id="iGxD7Bd" cx="0" cy="0" r="1" gradientTransform="matrix(-.42174 3.83665 -4.02032 -.44193 19.266 3.382)" gradientUnits="userSpaceOnUse"><stop class="iaf8w6bgr"/><stop offset="1" class="eb1rhabmt"/></radialGradient><radialGradient id="iDSuydk" cx="0" cy="0" r="1" gradientTransform="matrix(-.42173 2.35069 -3.94202 -.70722 20.415 10.587)" gradientUnits="userSpaceOnUse"><stop class="iaf8w6bgr"/><stop offset="1" class="eb1rhabmt"/></radialGradient><radialGradient id="i9mStdc" cx="0" cy="0" r="1" gradientTransform="matrix(-.42173 2.42806 -3.94974 -.68603 23.89 13.968)" gradientUnits="userSpaceOnUse"><stop class="iaf8w6bgr"/><stop offset="1" class="eb1rhabmt"/></radialGradient><radialGradient id="iZ6dPud" cx="0" cy="0" r="1" gradientTransform="rotate(100.14 5.978 19.932)scale(2.39543 4.00534)" gradientUnits="userSpaceOnUse"><stop class="iaf8w6bgr"/><stop offset="1" class="eb1rhabmt"/></radialGradient><linearGradient id="iA649Dc" x1="18.424" x2="17.793" y1="6.994" y2="17.833" gradientUnits="userSpaceOnUse"><stop class="pr-g-kbds"/><stop offset="1" class="oto_-lb9r"/></linearGradient><linearGradient id="iU1Enkc" x1="19.573" x2="19.348" y1="12.801" y2="19.625" gradientUnits="userSpaceOnUse"><stop class="pr-g-kbds"/><stop offset="1" class="oto_-lb9r"/></linearGradient><linearGradient id="iYOyyOQ" x1="23.048" x2="22.808" y1="16.255" y2="23.302" gradientUnits="userSpaceOnUse"><stop class="pr-g-kbds"/><stop offset="1" class="oto_-lb9r"/></linearGradient><linearGradient id="iGRQR5d" x1="25.809" x2="25.582" y1="19.777" y2="26.622" gradientUnits="userSpaceOnUse"><stop class="pr-g-kbds"/><stop offset="1" class="oto_-lb9r"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hand-with-index-finger-and-thumb-crossed" /></template>
<style>
.cjthqmk3i {
  stop-color: var(--svg-color--ffd942, #FFD942);
}

.cslhqcceg {
  stop-color: var(--svg-color--f8b645, #F8B645);
  stop-opacity: 0;
}

.df7civnnb {
  d: path("M9.586 7.52c.4 1.075.75 2.531.797 3.094l3.82-5.578c-.875-1.922-2.085-2.746-3.164-2.868c-1.25-.14-2.398.422-2.797 1.766c-.258 1.383.844 2.242 1.344 3.586");
}

.eb1rhabmt {
  stop-color: var(--svg-color--ffe763, #FFE763);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gtxgxst4i {
  stop-color: var(--svg-color--ffab61, #FFAB61);
}

.iaf8w6bgr {
  stop-color: var(--svg-color--ffe763, #FFE763);
}

.if18nilxg {
  stroke: var(--svg-color--ffa307, #FFA307);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M17.433 17.893a.22.22 0 0 0 .189.034a.3.3 0 0 0 .088-.04a1 1 0 0 0 .132-.104c.09-.082.203-.204.332-.353c.26-.3.596-.726.948-1.207c.351-.48.655-.93.862-1.268a5 5 0 0 0 .236-.425a1 1 0 0 0 .06-.156a.3.3 0 0 0 .01-.097a.22.22 0 0 0-.09-.17a.22.22 0 0 0-.19-.034a.3.3 0 0 0-.088.04a1 1 0 0 0-.131.104c-.09.082-.204.204-.333.353c-.26.3-.595.726-.947 1.207c-.352.48-.656.93-.862 1.269a5 5 0 0 0-.236.424a1 1 0 0 0-.06.156a.3.3 0 0 0-.01.096a.22.22 0 0 0 .09.17Z");
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

.jxixykbmj {
  stroke: var(--svg-color--ffa71e, #FFA71E);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.14 15.197c.092.068.19.033.212.025a.4.4 0 0 0 .085-.048q.066-.05.144-.129a7 7 0 0 0 .402-.45c.32-.383.74-.924 1.185-1.533a31 31 0 0 0 1.101-1.594c.133-.21.24-.388.307-.52q.052-.098.079-.176a.4.4 0 0 0 .02-.096a.22.22 0 0 0-.088-.195a.22.22 0 0 0-.213-.024a.4.4 0 0 0-.085.047a1.3 1.3 0 0 0-.144.129a7 7 0 0 0-.402.45c-.32.383-.74.924-1.186 1.533a31 31 0 0 0-1.1 1.594c-.133.21-.24.388-.307.52a1.3 1.3 0 0 0-.079.176a.4.4 0 0 0-.02.096a.22.22 0 0 0 .088.195Z");
}

.kaucbrclp {
  cx: 18.816px;
  cy: 16px;
  fill: var(--svg-color--ef9204, #EF9204);
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

.mfs7rhqip {
  cx: 14.863px;
  cy: 12.839px;
  fill: var(--svg-color--d37700, #D37700);
  rx: 0.178px;
  ry: 2.721px;
}

.ni69k2b3j {
  width: 3.917px;
  height: 16.515px;
  x: 16.28px;
  y: 2.357px;
  rx: 1.958px;
}

.oto_-lb9r {
  stop-color: var(--svg-color--ffcb54, #FFCB54);
  stop-opacity: 0;
}

.plaj5ybgu {
  stop-color: var(--svg-color--febe2c, #FEBE2C);
}

.pmyr8-pev {
  stop-color: var(--svg-color--dc9911, #DC9911);
}

.pr-g-kbds {
  stop-color: var(--svg-color--ffcb54, #FFCB54);
}

.t5crtj5dm {
  width: 3.917px;
  height: 10.15px;
  x: 23.665px;
  y: 16.927px;
  rx: 1.958px;
}

.wsjlisd8t {
  stop-color: var(--svg-color--f5ae44, #F5AE44);
}

.wt3q6zy0i {
  stroke: var(--svg-color--ffaf0c, #FFAF0C);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M20.693 20.542a.23.23 0 0 0 .167.04a.3.3 0 0 0 .091-.03a.7.7 0 0 0 .125-.087c.079-.067.176-.166.284-.285c.216-.24.491-.582.775-.97c.285-.39.527-.755.69-1.034a3 3 0 0 0 .185-.357a.7.7 0 0 0 .045-.145a.3.3 0 0 0 .001-.096a.23.23 0 0 0-.089-.147a.23.23 0 0 0-.167-.04a.3.3 0 0 0-.091.03a.7.7 0 0 0-.125.087a3 3 0 0 0-.284.284c-.216.24-.491.582-.775.97c-.285.39-.527.756-.69 1.035c-.081.138-.146.26-.185.356a.7.7 0 0 0-.045.145a.3.3 0 0 0-.001.097a.22.22 0 0 0 .089.147Z");
}

.xp_pabcho {
  cx: 21.83px;
  cy: 18.986px;
  fill: var(--svg-color--fa9b3a, #FA9B3A);
  rx: 0.178px;
  ry: 1.727px;
}

</style>
