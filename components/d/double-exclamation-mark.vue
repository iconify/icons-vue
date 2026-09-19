<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#idHuoJc)" class="k3cjv1bex"/><circle fill="url(#ix2lAde)" class="k3cjv1bex"/><circle fill="url(#iNEfH0b)" class="k3cjv1bex"/><circle fill="url(#iXzhpFe)" class="ywhhkf0ns"/><circle fill="url(#is57god)" class="ywhhkf0ns"/><circle fill="url(#i9yg5dc)" class="ywhhkf0ns"/><g filter="url(#iznL58b)"><path fill="url(#idxuD8m)" class="o4axa4blo"/><path fill="url(#iixcKRc)" class="o4axa4blo"/></g><g filter="url(#iZyNDQc)"><path fill="url(#ihciJvd)" class="nebzmj_gc"/><path fill="url(#ifvtT1p)" class="nebzmj_gc"/></g><g filter="url(#ilyAqUc)"><path stroke="url(#iznlBob)" class="kgwb9e8cj"/></g><g filter="url(#iM1Dqke)"><path stroke="url(#i85x7Me)" class="ajqxxk2vf"/></g><defs><radialGradient id="ix2lAde" cx="0" cy="0" r="1" gradientTransform="matrix(1.53125 -1.75 1.5386 1.34628 13.643 26.716)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="dcrsbbcfe"/><stop offset="1" class="npvh19b0x"/></radialGradient><radialGradient id="iNEfH0b" cx="0" cy="0" r="1" gradientTransform="matrix(2.5 1.21874 -3.2999 6.7691 10.175 25.154)" gradientUnits="userSpaceOnUse"><stop class="aaxt30sbu"/><stop offset="1" class="y461h2bjy"/></radialGradient><radialGradient id="is57god" cx="0" cy="0" r="1" gradientTransform="matrix(1.53125 -1.75 1.5386 1.34628 20.644 26.716)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="dcrsbbcfe"/><stop offset="1" class="npvh19b0x"/></radialGradient><radialGradient id="i9yg5dc" cx="0" cy="0" r="1" gradientTransform="matrix(2.5 1.21874 -3.2999 6.7691 17.175 25.154)" gradientUnits="userSpaceOnUse"><stop class="aaxt30sbu"/><stop offset="1" class="y461h2bjy"/></radialGradient><radialGradient id="iixcKRc" cx="0" cy="0" r="1" gradientTransform="rotate(148.241 6.912 3.671)scale(3.08727 2.21529)" gradientUnits="userSpaceOnUse"><stop class="pwewr5buv"/><stop offset="1" class="z0zlvqdzl"/></radialGradient><radialGradient id="ifvtT1p" cx="0" cy="0" r="1" gradientTransform="rotate(148.241 10.412 4.667)scale(3.08727 2.21529)" gradientUnits="userSpaceOnUse"><stop class="pwewr5buv"/><stop offset="1" class="z0zlvqdzl"/></radialGradient><linearGradient id="idHuoJc" x1="12.675" x2="12.675" y1="25.779" y2="29.564" gradientUnits="userSpaceOnUse"><stop class="kyy_-qs4j"/><stop offset="1" class="j8ie5mkwv"/></linearGradient><linearGradient id="iXzhpFe" x1="19.675" x2="19.675" y1="25.779" y2="29.564" gradientUnits="userSpaceOnUse"><stop class="kyy_-qs4j"/><stop offset="1" class="j8ie5mkwv"/></linearGradient><linearGradient id="idxuD8m" x1="12.675" x2="12.675" y1="2.098" y2="22.592" gradientUnits="userSpaceOnUse"><stop class="kqjz1wbgv"/><stop offset="1" class="i76s0ubvh"/></linearGradient><linearGradient id="ihciJvd" x1="19.675" x2="19.675" y1="2.098" y2="22.592" gradientUnits="userSpaceOnUse"><stop class="kqjz1wbgv"/><stop offset="1" class="i76s0ubvh"/></linearGradient><linearGradient id="iznlBob" x1="14.041" x2="18.666" y1="22.12" y2="20.92" gradientUnits="userSpaceOnUse"><stop class="ycqx-0fln"/><stop offset="1" class="h0z_c4bkg"/></linearGradient><linearGradient id="i85x7Me" x1="21.041" x2="25.666" y1="22.12" y2="20.92" gradientUnits="userSpaceOnUse"><stop class="ycqx-0fln"/><stop offset="1" class="h0z_c4bkg"/></linearGradient><filter id="iznL58b" width="5.75" height="21.719" x="10.175" y="1.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.160784 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1778"/></filter><filter id="iZyNDQc" width="5.75" height="21.719" x="17.175" y="1.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.160784 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1778"/></filter><filter id="ilyAqUc" width="5" height="20.188" x="10.847" y="2.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1778" stdDeviation=".75"/></filter><filter id="iM1Dqke" width="5" height="20.188" x="17.847" y="2.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1778" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:double-exclamation-mark" /></template>
<style>
.aaxt30sbu {
  stop-color: var(--svg-color--c8404b, #C8404B);
}

.ajqxxk2vf {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20.347 20.53V5.341");
}

.dcrsbbcfe {
  stop-color: var(--svg-color--ff5878, #FF5878);
}

.ft5dv1b6b {
  fill: none;
}

.h0z_c4bkg {
  stop-color: var(--svg-color--ff3e59, #FF3E59);
}

.i76s0ubvh {
  stop-color: var(--svg-color--f41585, #F41585);
}

.j8ie5mkwv {
  stop-color: var(--svg-color--f62093, #F62093);
}

.k3cjv1bex {
  cx: 12.675px;
  cy: 27.064px;
  r: 2.5px;
}

.kgwb9e8cj {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.347 20.53V5.341");
}

.kqjz1wbgv {
  stop-color: var(--svg-color--ed1f28, #ED1F28);
}

.kyy_-qs4j {
  stop-color: var(--svg-color--ff0b38, #FF0B38);
}

.nebzmj_gc {
  d: path("M17.175 4.123a2.5 2.5 0 0 1 5 0v15.969a2.5 2.5 0 1 1-5 0z");
}

.npvh19b0x {
  stop-color: var(--svg-color--ff5878, #FF5878);
  stop-opacity: 0;
}

.o4axa4blo {
  d: path("M10.175 4.123a2.5 2.5 0 0 1 5 0v15.969a2.5 2.5 0 1 1-5 0z");
}

.pwewr5buv {
  stop-color: var(--svg-color--ff5960, #FF5960);
}

.y461h2bjy {
  stop-color: var(--svg-color--c8404b, #C8404B);
  stop-opacity: 0;
}

.ycqx-0fln {
  stop-color: var(--svg-color--ff4282, #FF4282);
}

.ywhhkf0ns {
  cx: 19.675px;
  cy: 27.064px;
  r: 2.5px;
}

.z0zlvqdzl {
  stop-color: var(--svg-color--ff5960, #FF5960);
  stop-opacity: 0;
}

</style>
