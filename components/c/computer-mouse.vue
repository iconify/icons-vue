<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iH6TPwq)"><path fill="url(#iEeKbze)" class="o-r4adb3b"/><path fill="url(#iiZQbOe)" class="o-r4adb3b"/></g><path fill="url(#ihzFDEe)" class="o-r4adb3b"/><g filter="url(#ifCrrfb)"><path class="ii_e9hhkh"/></g><g filter="url(#i81Queb)"><path fill="url(#iDbXIWc)" class="b00m8xlnd"/></g><path fill="url(#izMJkPe)" class="cay6djbbp"/><path fill="url(#ijxzdYd)" class="cay6djbbp"/><path fill="url(#iGjl5Id)" class="cay6djbbp"/><defs><radialGradient id="iEeKbze" cx="0" cy="0" r="1" gradientTransform="matrix(0 19.375 -13.1875 0 23.125 9.75)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="onf_p2kru"/><stop offset="1" class="b6vd90bff"/><stop offset="1" class="b6vd90bff"/></radialGradient><radialGradient id="iiZQbOe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.0625 27.1605 0 15.996 29.938)" gradientUnits="userSpaceOnUse"><stop class="hdg814bfp"/><stop offset="1" class="x4da8qbzn"/></radialGradient><radialGradient id="iDbXIWc" cx="0" cy="0" r="1" gradientTransform="matrix(0 10 -1.45792 0 16.564 7.219)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="qe_nrwybn"/><stop offset="1" class="utxtwu98y"/></radialGradient><radialGradient id="ijxzdYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.10938 -2.25 0 17.828 8.688)" gradientUnits="userSpaceOnUse"><stop class="zm9wbcb_e"/><stop offset="1" class="lntshsb-q"/></radialGradient><radialGradient id="iGjl5Id" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.17188 -.4375 0 17.438 8.61)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="grjcfi_rz"/><stop offset="1" class="o7l0webkr"/></radialGradient><filter id="iH6TPwq" width="18.252" height="28.275" x="6.87" y="1.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.635294 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19739"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.952941 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19739" result="effect2_innerShadow_18_19739"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.568627 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19739" result="effect3_innerShadow_18_19739"/></filter><filter id="ifCrrfb" width="5.086" height="8.07" x="12.885" y="4.914" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19739" stdDeviation=".5"/></filter><filter id="i81Queb" width="1.187" height="12.953" x="15.428" y="2.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.596078 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19739"/></filter><linearGradient id="ihzFDEe" x1="25.094" x2="24.672" y1="16" y2="16" gradientUnits="userSpaceOnUse"><stop offset=".407" class="nw6pt4bpo"/><stop offset="1" class="tjzsambum"/></linearGradient><linearGradient id="izMJkPe" x1="16" x2="16" y1="5.914" y2="12.281" gradientUnits="userSpaceOnUse"><stop class="des1hcvho"/><stop offset="1" class="f5_gqusbv"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:computer-mouse" /></template>
<style>
.b00m8xlnd {
  d: path("M16.565 2.063v12.384a.568.568 0 0 1-1.137 0V2.063z");
}

.b6vd90bff {
  stop-color: var(--svg-color--d0ced2, #D0CED2);
}

.cay6djbbp {
  d: path("M14.457 6.164a.25.25 0 0 1 .25-.25h2.586a.25.25 0 0 1 .25.25v5.57a.25.25 0 0 1-.25.25h-2.586a.25.25 0 0 1-.25-.25z");
}

.des1hcvho {
  stop-color: var(--svg-color--a3a3a4, #A3A3A4);
}

.f5_gqusbv {
  stop-color: var(--svg-color--928d98, #928D98);
}

.ft5dv1b6b {
  fill: none;
}

.grjcfi_rz {
  stop-color: var(--svg-color--b2b1b4, #B2B1B4);
}

.hdg814bfp {
  stop-color: var(--svg-color--afa0bf, #AFA0BF);
}

.ii_e9hhkh {
  fill: var(--svg-color--c3c1c5, #C3C1C5);
  d: path("M13.885 6.164a.25.25 0 0 1 .25-.25h2.586a.25.25 0 0 1 .25.25v5.57a.25.25 0 0 1-.25.25h-2.586a.25.25 0 0 1-.25-.25z");
}

.lntshsb-q {
  stop-color: var(--svg-color--a7a5a8, #A7A5A8);
  stop-opacity: 0;
}

.nw6pt4bpo {
  stop-color: var(--svg-color--e0dfe1, #E0DFE1);
}

.o-r4adb3b {
  d: path("M7.07 6.763a4.7 4.7 0 0 1 4.7-4.7h8.452a4.7 4.7 0 0 1 4.7 4.7v18.675a4.5 4.5 0 0 1-4.5 4.5H11.57a4.5 4.5 0 0 1-4.5-4.5z");
}

.o7l0webkr {
  stop-color: var(--svg-color--a9a7aa, #A9A7AA);
  stop-opacity: 0;
}

.onf_p2kru {
  stop-color: var(--svg-color--e9e8eb, #E9E8EB);
}

.qe_nrwybn {
  stop-color: var(--svg-color--8e8d8f, #8E8D8F);
}

.tjzsambum {
  stop-color: var(--svg-color--e0dfe1, #E0DFE1);
  stop-opacity: 0;
}

.utxtwu98y {
  stop-color: var(--svg-color--a1a0a1, #A1A0A1);
}

.x4da8qbzn {
  stop-color: var(--svg-color--c9c4ce, #C9C4CE);
  stop-opacity: 0;
}

.zm9wbcb_e {
  stop-color: var(--svg-color--a7a5a8, #A7A5A8);
}

</style>
