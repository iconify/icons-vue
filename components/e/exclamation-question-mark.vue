<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#iTmG2Kb)" class="t0nimabaq"/><circle fill="url(#ic6Z9je)" class="t0nimabaq"/><circle fill="url(#iQuXrJo)" class="t0nimabaq"/><circle fill="url(#ipFZL7b)" class="x13_0xbii"/><circle fill="url(#iNOMHSb)" class="x13_0xbii"/><circle fill="url(#iBJK5yJ)" class="x13_0xbii"/><g filter="url(#ijPnlMi)"><path fill="url(#igcC7Me)" class="m9svlwb5v"/><path fill="url(#iiqafxb)" class="m9svlwb5v"/></g><g filter="url(#iL8yjZb)"><path fill="url(#i3XKcEe)" clip-rule="evenodd" class="c8kqpq0cr"/></g><g filter="url(#iJt35Vd)" class="e3fsewyjy"><path stroke="url(#iX2qGlc)" class="pjlv6yb-v"/><path stroke="url(#iGAofLb)" class="pjlv6yb-v"/></g><g filter="url(#iG7LMfe)"><path stroke="url(#i0XOPPb)" class="qjuqt7b6q"/></g><defs><linearGradient id="iTmG2Kb" x1="8.587" x2="8.587" y1="26.188" y2="29.973" gradientUnits="userSpaceOnUse"><stop class="kyy_-qs4j"/><stop offset="1" class="j8ie5mkwv"/></linearGradient><linearGradient id="ipFZL7b" x1="20.587" x2="20.587" y1="26.188" y2="29.973" gradientUnits="userSpaceOnUse"><stop class="kyy_-qs4j"/><stop offset="1" class="j8ie5mkwv"/></linearGradient><linearGradient id="igcC7Me" x1="8.587" x2="8.587" y1="2.507" y2="23" gradientUnits="userSpaceOnUse"><stop class="kqjz1wbgv"/><stop offset="1" class="i76s0ubvh"/></linearGradient><linearGradient id="i3XKcEe" x1="21.079" x2="21.079" y1="2.563" y2="23.391" gradientUnits="userSpaceOnUse"><stop class="kqjz1wbgv"/><stop offset="1" class="i76s0ubvh"/></linearGradient><linearGradient id="iX2qGlc" x1="27.446" x2="22.759" y1="7.25" y2="11.125" gradientUnits="userSpaceOnUse"><stop offset=".103" class="bsa6cxs1i"/><stop offset="1" class="yjqpvi6jt"/></linearGradient><linearGradient id="iGAofLb" x1="23.759" x2="27.102" y1="21.5" y2="13.75" gradientUnits="userSpaceOnUse"><stop class="qdbbpp3-r"/><stop offset="1" class="vr4ufs7kt"/></linearGradient><linearGradient id="i0XOPPb" x1="9.952" x2="14.577" y1="22.528" y2="21.328" gradientUnits="userSpaceOnUse"><stop class="ycqx-0fln"/><stop offset="1" class="h0z_c4bkg"/></linearGradient><radialGradient id="ic6Z9je" cx="0" cy="0" r="1" gradientTransform="matrix(1.53125 -1.75 1.5386 1.34627 9.555 27.125)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="dcrsbbcfe"/><stop offset="1" class="npvh19b0x"/></radialGradient><radialGradient id="iQuXrJo" cx="0" cy="0" r="1" gradientTransform="matrix(2.5 1.21875 -3.29992 6.76908 6.087 25.563)" gradientUnits="userSpaceOnUse"><stop class="aaxt30sbu"/><stop offset="1" class="y461h2bjy"/></radialGradient><radialGradient id="iNOMHSb" cx="0" cy="0" r="1" gradientTransform="matrix(1.53125 -1.75 1.5386 1.34627 21.555 27.125)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="dcrsbbcfe"/><stop offset="1" class="npvh19b0x"/></radialGradient><radialGradient id="iBJK5yJ" cx="0" cy="0" r="1" gradientTransform="matrix(2.5 1.21874 -3.2999 6.7691 18.087 25.562)" gradientUnits="userSpaceOnUse"><stop class="aaxt30sbu"/><stop offset="1" class="y461h2bjy"/></radialGradient><radialGradient id="iiqafxb" cx="0" cy="0" r="1" gradientTransform="rotate(148.241 4.81 3.294)scale(3.08727 2.21529)" gradientUnits="userSpaceOnUse"><stop class="pwewr5buv"/><stop offset="1" class="z0zlvqdzl"/></radialGradient><filter id="ijPnlMi" width="5.75" height="21.719" x="6.087" y="2.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.160784 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1792"/></filter><filter id="iL8yjZb" width="16.672" height="22.061" x="13.118" y="2.079" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.180392 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1792"/></filter><filter id="iJt35Vd" width="15.922" height="20.515" x="13.68" y="1.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1792" stdDeviation=".75"/></filter><filter id="iG7LMfe" width="5" height="20.188" x="6.758" y="3.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1792" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:exclamation-question-mark" /></template>
<style>
.aaxt30sbu {
  stop-color: var(--svg-color--c8404b, #C8404B);
}

.bsa6cxs1i {
  stop-color: var(--svg-color--ff5867, #FF5867);
}

.c8kqpq0cr {
  fill-rule: evenodd;
  d: path("M20.311 7.152c-.946.225-1.45.655-1.736 1.05c-.32.44-.457.965-.457 1.407a2.5 2.5 0 1 1-5 0c0-2.793 1.715-6.34 6.133-7.344l.098-.02c2.888-.536 5.41.255 7.181 1.984c1.702 1.661 2.51 3.989 2.51 6.255c0 2.253-.648 4.093-2.118 5.654c-1.012 1.074-2.354 1.942-3.851 2.761v1.992a2.5 2.5 0 0 1-5 0v-3.5a2.5 2.5 0 0 1 1.362-2.226c2.088-1.068 3.207-1.773 3.85-2.455c.482-.513.757-1.072.757-2.226c0-1.14-.412-2.1-1.002-2.677c-.517-.504-1.348-.898-2.727-.655");
}

.dcrsbbcfe {
  stop-color: var(--svg-color--ff5878, #FF5878);
}

.e3fsewyjy {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
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

.kqjz1wbgv {
  stop-color: var(--svg-color--ed1f28, #ED1F28);
}

.kyy_-qs4j {
  stop-color: var(--svg-color--ff0b38, #FF0B38);
}

.m9svlwb5v {
  d: path("M6.087 4.531a2.5 2.5 0 0 1 5 0V20.5a2.5 2.5 0 0 1-5 0z");
}

.npvh19b0x {
  stop-color: var(--svg-color--ff5878, #FF5878);
  stop-opacity: 0;
}

.pjlv6yb-v {
  d: path("M16.18 9.39c0-1.828 1.094-4.203 4.188-4.906c4.297-.797 6.734 2.375 6.734 5.781s-1.843 4.797-5.968 6.907v2.703");
}

.pwewr5buv {
  stop-color: var(--svg-color--ff5960, #FF5960);
}

.qdbbpp3-r {
  stop-color: var(--svg-color--ff3c80, #FF3C80);
}

.qjuqt7b6q {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.258 20.938V5.75");
}

.t0nimabaq {
  cx: 8.587px;
  cy: 27.473px;
  r: 2.5px;
}

.vr4ufs7kt {
  stop-color: var(--svg-color--ff3c80, #FF3C80);
  stop-opacity: 0;
}

.x13_0xbii {
  cx: 20.587px;
  cy: 27.473px;
  r: 2.5px;
}

.y461h2bjy {
  stop-color: var(--svg-color--c8404b, #C8404B);
  stop-opacity: 0;
}

.ycqx-0fln {
  stop-color: var(--svg-color--ff4282, #FF4282);
}

.yjqpvi6jt {
  stop-color: var(--svg-color--ff5867, #FF5867);
  stop-opacity: 0;
}

.z0zlvqdzl {
  stop-color: var(--svg-color--ff5960, #FF5960);
  stop-opacity: 0;
}

</style>
