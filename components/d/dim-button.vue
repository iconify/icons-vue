<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i69vLje)"><path class="d72_vqg6c"/></g><g filter="url(#iROX0be)"><path fill="url(#ip0xE6d)" class="dz10q0bmh"/></g><g filter="url(#iASUlBc)"><path fill="url(#iSHcyXM)" class="izye0ykav"/></g><g filter="url(#iQAA21T)"><path fill="url(#ismGLbe)" class="s9khjab7m"/></g><g filter="url(#i4fLTpb)"><path fill="url(#iwtadhb)" class="jbmpi9bno"/></g><g filter="url(#iIUOgod)"><path fill="url(#ii2oOAb)" class="kquzj6bis"/></g><g filter="url(#iHN5Adb)"><path fill="url(#i6e4EWC)" class="jjphh35nk"/></g><g filter="url(#ikbtwcc)"><path fill="url(#iKM0zpe)" class="aslamobva"/></g><g filter="url(#iWG2UBa)"><path fill="url(#iqtFbhz)" class="xqj76cu0i"/></g><g filter="url(#irYx3zb)"><ellipse stroke="url(#ioAPSwe)" class="t_l6g-j_f"/><ellipse stroke="url(#iIVxROd)" class="t_l6g-j_f"/></g><defs><filter id="i69vLje" width="17.46" height="17.46" x="7.77" y="6.405" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.466667 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1588"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.345098 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1588" result="effect2_innerShadow_18590_1588"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.501961 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18590_1588" result="effect3_innerShadow_18590_1588"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.396078 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_18590_1588" result="effect4_innerShadow_18590_1588"/></filter><filter id="iROX0be" width="4.22" height="4.22" x="5.48" y="5.015" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.380392 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1588"/></filter><filter id="iASUlBc" width="4.22" height="4.22" x="2.13" y="13.535" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.380392 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1588"/></filter><filter id="iQAA21T" width="4.22" height="4.22" x="5.79" y="21.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.380392 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1588"/></filter><filter id="i4fLTpb" width="4.22" height="4.22" x="14.31" y="25.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.380392 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1588"/></filter><filter id="iIUOgod" width="4.22" height="4.22" x="22.71" y="21.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.380392 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1588"/></filter><filter id="iHN5Adb" width="4.22" height="4.22" x="26.05" y="13.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.380392 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1588"/></filter><filter id="ikbtwcc" width="4.22" height="4.22" x="22.4" y="4.705" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.380392 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1588"/></filter><filter id="iWG2UBa" width="4.22" height="4.22" x="13.87" y="1.355" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.380392 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1588"/></filter><filter id="irYx3zb" width="15.921" height="15.931" x="8.288" y="7.306" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1588" stdDeviation=".325"/></filter><radialGradient id="ip0xE6d" cx="0" cy="0" r="1" gradientTransform="rotate(137.891 2.965 4.907)scale(2.1904)" gradientUnits="userSpaceOnUse"><stop offset=".151" class="g8tr8tjej"/><stop offset="1" class="ikynyfbtj"/></radialGradient><radialGradient id="iSHcyXM" cx="0" cy="0" r="1" gradientTransform="rotate(137.891 -.35 8.523)scale(2.1904)" gradientUnits="userSpaceOnUse"><stop offset=".151" class="g8tr8tjej"/><stop offset="1" class="ikynyfbtj"/></radialGradient><radialGradient id="ismGLbe" cx="0" cy="0" r="1" gradientTransform="rotate(137.891 -.137 13.427)scale(2.1904)" gradientUnits="userSpaceOnUse"><stop offset=".151" class="g8tr8tjej"/><stop offset="1" class="ikynyfbtj"/></radialGradient><radialGradient id="iwtadhb" cx="0" cy="0" r="1" gradientTransform="rotate(137.891 3.48 16.737)scale(2.1904)" gradientUnits="userSpaceOnUse"><stop offset=".151" class="g8tr8tjej"/><stop offset="1" class="ikynyfbtj"/></radialGradient><radialGradient id="ii2oOAb" cx="0" cy="0" r="1" gradientTransform="rotate(137.891 8.383 16.529)scale(2.1904)" gradientUnits="userSpaceOnUse"><stop offset=".151" class="g8tr8tjej"/><stop offset="1" class="ikynyfbtj"/></radialGradient><radialGradient id="i6e4EWC" cx="0" cy="0" r="1" gradientTransform="rotate(137.891 11.695 12.907)scale(2.1904)" gradientUnits="userSpaceOnUse"><stop offset=".151" class="g8tr8tjej"/><stop offset="1" class="ikynyfbtj"/></radialGradient><radialGradient id="iKM0zpe" cx="0" cy="0" r="1" gradientTransform="rotate(137.891 11.485 8.01)scale(2.1904)" gradientUnits="userSpaceOnUse"><stop offset=".151" class="g8tr8tjej"/><stop offset="1" class="ikynyfbtj"/></radialGradient><radialGradient id="iqtFbhz" cx="0" cy="0" r="1" gradientTransform="rotate(137.891 7.864 4.692)scale(2.1904)" gradientUnits="userSpaceOnUse"><stop offset=".151" class="g8tr8tjej"/><stop offset="1" class="ikynyfbtj"/></radialGradient><linearGradient id="ioAPSwe" x1="21.228" x2="16.244" y1="9.428" y2="15.268" gradientUnits="userSpaceOnUse"><stop class="kzn48qjvo"/><stop offset="1" class="xxxa8cbud"/></linearGradient><linearGradient id="iIVxROd" x1="11.332" x2="14.006" y1="20.851" y2="17.328" gradientUnits="userSpaceOnUse"><stop class="kzn48qjvo"/><stop offset="1" class="xxxa8cbud"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:dim-button" /></template>
<style>
.aslamobva {
  d: path("M26.22 7.015a1.91 1.91 0 1 1-3.82 0a1.91 1.91 0 0 1 3.82 0");
}

.d72_vqg6c {
  fill: var(--svg-color--ff9b5a, #FF9B5A);
  d: path("M16 23.865c-4.54 0-8.23-3.69-8.23-8.23s3.69-8.23 8.23-8.23s8.23 3.69 8.23 8.23s-3.69 8.23-8.23 8.23m0-13.47a5.24 5.24 0 0 0-5.23 5.23a5.24 5.24 0 0 0 5.23 5.23a5.24 5.24 0 0 0 5.23-5.23c0-2.88-2.34-5.23-5.23-5.23");
}

.dz10q0bmh {
  d: path("M9.3 7.325a1.91 1.91 0 1 1-3.82 0a1.91 1.91 0 0 1 3.82 0");
}

.ft5dv1b6b {
  fill: none;
}

.g8tr8tjej {
  stop-color: var(--svg-color--ffbf76, #FFBF76);
}

.ikynyfbtj {
  stop-color: var(--svg-color--ff9250, #FF9250);
}

.izye0ykav {
  d: path("M4.04 17.755a1.91 1.91 0 1 0 0-3.82a1.91 1.91 0 0 0 0 3.82");
}

.jbmpi9bno {
  d: path("M16.22 29.495a1.91 1.91 0 1 0 0-3.82a1.91 1.91 0 0 0 0 3.82");
}

.jjphh35nk {
  d: path("M27.96 17.315a1.91 1.91 0 1 0 0-3.82a1.91 1.91 0 0 0 0 3.82");
}

.kquzj6bis {
  d: path("M26.53 23.935a1.91 1.91 0 1 1-3.82 0a1.91 1.91 0 0 1 3.82 0");
}

.kzn48qjvo {
  stop-color: var(--svg-color--ffbe77, #FFBE77);
}

.s9khjab7m {
  d: path("M9.61 24.245a1.91 1.91 0 1 1-3.82 0a1.91 1.91 0 0 1 3.82 0");
}

.t_l6g-j_f {
  cx: 16.249px;
  cy: 15.272px;
  rx: 6.811px;
  ry: 6.816px;
}

.xqj76cu0i {
  d: path("M15.78 5.575a1.91 1.91 0 1 0 0-3.82a1.91 1.91 0 0 0 0 3.82");
}

.xxxa8cbud {
  stop-color: var(--svg-color--ffbe77, #FFBE77);
  stop-opacity: 0;
}

</style>
