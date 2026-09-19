<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iIoiwme)"><path fill="url(#ifleJjd)" class="rt3z2_ddr"/></g><g filter="url(#iBoAeCb)"><path fill="url(#icExwYc)" class="b981dbc3i"/></g><g filter="url(#i5wBlKd)"><path fill="url(#ibHrX6b)" class="vo06jov6i"/></g><g filter="url(#ibnl9Wd)"><path fill="url(#iJKR6be)" clip-rule="evenodd" class="l2z1okbdk"/></g><g filter="url(#iwzbl4d)"><path fill="url(#igzCvpc)" clip-rule="evenodd" class="i08-jnnaj"/></g><g filter="url(#iJHhTnc)"><path fill="url(#iPdnNTb)" clip-rule="evenodd" class="xd1e89bsd"/></g><g filter="url(#ih05Nnc)"><path fill="url(#innqOgb)" class="sm7vrab8r"/></g><g filter="url(#inkdKLb)"><path fill="url(#imkaoPc)" class="bv1dg72cb"/></g><g filter="url(#iHVCMjc)"><path fill="url(#iJjphvc)" class="wg4ujzk2q"/></g><defs><filter id="iIoiwme" width="29" height="19" x="1.5" y="11.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.545098 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4793_1073"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.956863 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4793_1073" result="effect2_innerShadow_4793_1073"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.45098 0 0 0 0 0.666667 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4793_1073" result="effect3_innerShadow_4793_1073"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.85098 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_4793_1073" result="effect4_innerShadow_4793_1073"/></filter><filter id="iBoAeCb" width="13.2" height="3.2" x="13.95" y="24.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.588235 0 0 0 0 0.690196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4793_1073"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4793_1073" result="effect2_innerShadow_4793_1073"/></filter><filter id="i5wBlKd" width="10.2" height="1.2" x="15" y="25.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.654902 0 0 0 0 0.615686 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4793_1073"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4793_1073" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.305882 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4793_1073"/></filter><filter id="ibnl9Wd" width="13.3" height="1.15" x="13.9" y="20.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.380392 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4793_1073"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.317647 0 0 0 0 0.54902 0 0 0 0 0.913725 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4793_1073" result="effect2_innerShadow_4793_1073"/></filter><filter id="iwzbl4d" width="13.3" height="1.15" x="13.9" y="17.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.380392 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4793_1073"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.317647 0 0 0 0 0.54902 0 0 0 0 0.913725 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4793_1073" result="effect2_innerShadow_4793_1073"/></filter><filter id="iJHhTnc" width="13.4" height="1.15" x="13.8" y="14.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.380392 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4793_1073"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.317647 0 0 0 0 0.54902 0 0 0 0 0.913725 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4793_1073" result="effect2_innerShadow_4793_1073"/></filter><filter id="ih05Nnc" width="8.453" height="10.469" x="3.754" y="13.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4793_1073" stdDeviation=".125"/></filter><filter id="inkdKLb" width="8.053" height="10.069" x="4.013" y="13.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.588235 0 0 0 0 0.690196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4793_1073"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4793_1073" result="effect2_innerShadow_4793_1073"/></filter><filter id="iHVCMjc" width="8.153" height="8.781" x="3.962" y="15.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.160784 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4793_1073"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.278431 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4793_1073" result="effect2_innerShadow_4793_1073"/></filter><linearGradient id="ifleJjd" x1="16.016" x2="16.016" y1="13.498" y2="30.015" gradientUnits="userSpaceOnUse"><stop class="xurcclvjz"/><stop offset="1" class="x-xxusgwq"/></linearGradient><linearGradient id="icExwYc" x1="14.656" x2="26.344" y1="27.248" y2="27.248" gradientUnits="userSpaceOnUse"><stop class="s6j8uv6ej"/><stop offset="1" class="q1xyxsblp"/></linearGradient><linearGradient id="ibHrX6b" x1="15.065" x2="25.058" y1="26.497" y2="26.497" gradientUnits="userSpaceOnUse"><stop class="icqq61boa"/><stop offset="1" class="cw1vrerbd"/></linearGradient><linearGradient id="innqOgb" x1="7.98" x2="7.98" y1="14.047" y2="24.016" gradientUnits="userSpaceOnUse"><stop class="u00jo4t6h"/><stop offset="1" class="j51n9jzvj"/></linearGradient><linearGradient id="imkaoPc" x1="8.906" x2="8.906" y1="22.904" y2="14.56" gradientUnits="userSpaceOnUse"><stop class="e_v_9frtf"/><stop offset="1" class="k_cgx249y"/></linearGradient><linearGradient id="iJjphvc" x1="8.039" x2="8.039" y1="16.154" y2="23.967" gradientUnits="userSpaceOnUse"><stop class="yh2x-lbmv"/><stop offset="1" class="ppfftccdg"/></linearGradient><radialGradient id="iJKR6be" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.28125 -13.2812 0 25.063 21.217)" gradientUnits="userSpaceOnUse"><stop class="v0uysbp1v"/><stop offset="1" class="qjqs4-z6a"/></radialGradient><radialGradient id="igzCvpc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.28125 -13.2812 0 25.063 18.217)" gradientUnits="userSpaceOnUse"><stop class="v0uysbp1v"/><stop offset="1" class="qjqs4-z6a"/></radialGradient><radialGradient id="iPdnNTb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.28125 -13.3826 0 25.047 15.217)" gradientUnits="userSpaceOnUse"><stop class="v0uysbp1v"/><stop offset="1" class="qjqs4-z6a"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:identification-card" /></template>
<style>
.b981dbc3i {
  d: path("M26.5 28H14.6c-.3 0-.6-.2-.6-.6v-1.9c0-.3.2-.6.6-.6h11.9c.3 0 .6.2.6.6v1.9c0 .3-.3.6-.6.6");
}

.bv1dg72cb {
  d: path("M4.063 14.498a.5.5 0 0 1 .5-.5h6.953a.5.5 0 0 1 .5.5v8.969a.5.5 0 0 1-.5.5H4.563a.5.5 0 0 1-.5-.5z");
}

.cw1vrerbd {
  stop-color: var(--svg-color--2f2c31, #2F2C31);
}

.e_v_9frtf {
  stop-color: var(--svg-color--e2ddde, #E2DDDE);
}

.ft5dv1b6b {
  fill: none;
}

.i08-jnnaj {
  fill-rule: evenodd;
  d: path("M14 18.5a.5.5 0 0 1 .5-.5h12.1a.5.5 0 0 1 0 1H14.5a.5.5 0 0 1-.5-.5");
}

.icqq61boa {
  stop-color: var(--svg-color--41344a, #41344A);
}

.j51n9jzvj {
  stop-color: var(--svg-color--267cb6, #267CB6);
}

.k_cgx249y {
  stop-color: var(--svg-color--e3dddf, #E3DDDF);
}

.l2z1okbdk {
  fill-rule: evenodd;
  d: path("M14 21.5a.5.5 0 0 1 .5-.5h12.1a.5.5 0 0 1 0 1H14.5a.5.5 0 0 1-.5-.5");
}

.ppfftccdg {
  stop-color: var(--svg-color--372e3c, #372E3C);
}

.q1xyxsblp {
  stop-color: var(--svg-color--e5e3e0, #E5E3E0);
}

.qjqs4-z6a {
  stop-color: var(--svg-color--3375cd, #3375CD);
}

.rt3z2_ddr {
  d: path("M27.8 30H4.2C3 30 2 29 2 27.8V14.2C2 13 3 12 4.2 12h23.5c1.3 0 2.3 1 2.3 2.2v13.5c0 1.3-1 2.3-2.2 2.3");
}

.s6j8uv6ej {
  stop-color: var(--svg-color--e5dfdf, #E5DFDF);
}

.sm7vrab8r {
  d: path("M4.004 14.547a.5.5 0 0 1 .5-.5h6.953a.5.5 0 0 1 .5.5v8.969a.5.5 0 0 1-.5.5H4.504a.5.5 0 0 1-.5-.5z");
}

.u00jo4t6h {
  stop-color: var(--svg-color--44b3d6, #44B3D6);
}

.v0uysbp1v {
  stop-color: var(--svg-color--3476ce, #3476CE);
}

.vo06jov6i {
  d: path("M24.6 27h-9c-.3 0-.5-.2-.5-.5s.2-.5.5-.5h9c.3 0 .5.2.5.5s-.3.5-.5.5");
}

.wg4ujzk2q {
  d: path("M12.016 23.263v.204a.5.5 0 0 1-.5.5H4.563a.5.5 0 0 1-.5-.5v-.204c.536-1.22 1.653-1.893 2.683-2.233c.049-.016.047-.097-.001-.116a1.2 1.2 0 0 1-.763-1.071l-.03-.763h-.007a.738.738 0 0 1-.05-1.475l-.039-.965a1.4 1.4 0 0 1 1.4-1.455h1.489c.8 0 1.515.67 1.476 1.468l-.046.953a.738.738 0 0 1-.058 1.474h-.013l-.029.6c-.026.559-.322 1.027-.78 1.228c-.047.02-.046.095.002.11c1.039.337 2.176 1.01 2.719 2.245");
}

.x-xxusgwq {
  stop-color: var(--svg-color--39a6e8, #39A6E8);
}

.xd1e89bsd {
  fill-rule: evenodd;
  d: path("M13.9 15.5a.5.5 0 0 1 .5-.5h12.2a.5.5 0 1 1 0 1H14.4a.5.5 0 0 1-.5-.5");
}

.xurcclvjz {
  stop-color: var(--svg-color--57d2f0, #57D2F0);
}

.yh2x-lbmv {
  stop-color: var(--svg-color--44354f, #44354F);
}

</style>
