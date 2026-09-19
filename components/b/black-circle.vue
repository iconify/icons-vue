<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iRK04sc)" class="hy4x1nb-j"/><path fill="url(#iP9lurd)" class="hy4x1nb-j"/><path fill="url(#isfWXVc)" class="hy4x1nb-j"/><path fill="url(#ieNQ2Wc)" class="hy4x1nb-j"/><path fill="url(#iJwWKBd)" class="hy4x1nb-j"/><defs><radialGradient id="iRK04sc" cx="0" cy="0" r="1" gradientTransform="rotate(130.168 9.831 9.886)scale(27.8086)" gradientUnits="userSpaceOnUse"><stop class="ll2cae_nt"/><stop offset=".662" class="dhmrozbns"/></radialGradient><radialGradient id="isfWXVc" cx="0" cy="0" r="1" gradientTransform="matrix(-9.47663 8.74999 -8.07914 -8.75007 24.227 10.75)" gradientUnits="userSpaceOnUse"><stop offset=".113" class="bf5_hdm8l"/><stop offset="1" class="i66nxkr1h"/></radialGradient><radialGradient id="ieNQ2Wc" cx="0" cy="0" r="1" gradientTransform="matrix(-19.25 0 0 -20 20.04 16)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="lnenc8_pr"/><stop offset=".951" class="d6f68ab6r"/></radialGradient><radialGradient id="iJwWKBd" cx="0" cy="0" r="1" gradientTransform="matrix(0 21.8837 -24.3022 0 15.547 9)" gradientUnits="userSpaceOnUse"><stop offset=".853" class="sph0v-2nh"/><stop offset="1" class="wbe-qab5p"/></radialGradient><linearGradient id="iP9lurd" x1="15.547" x2="15.547" y1="2" y2="8.5" gradientUnits="userSpaceOnUse"><stop class="ujq3xtbnv"/><stop offset="1" class="zi0bqjbqb"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:black-circle" /></template>
<style>
.bf5_hdm8l {
  stop-color: var(--svg-color--6a6571, #6A6571);
}

.d6f68ab6r {
  stop-color: var(--svg-color--8c8b8d, #8C8B8D);
}

.dhmrozbns {
  stop-color: var(--svg-color--33293d, #33293D);
}

.ft5dv1b6b {
  fill: none;
}

.hy4x1nb-j {
  d: path("M29.547 16c0 7.732-6.268 14-14 14s-14-6.268-14-14s6.268-14 14-14s14 6.268 14 14");
}

.i66nxkr1h {
  stop-color: var(--svg-color--49474c, #49474C);
  stop-opacity: 0;
}

.ll2cae_nt {
  stop-color: var(--svg-color--645b70, #645B70);
}

.lnenc8_pr {
  stop-color: var(--svg-color--434344, #434344);
  stop-opacity: 0;
}

.sph0v-2nh {
  stop-color: var(--svg-color--352343, #352343);
  stop-opacity: 0;
}

.ujq3xtbnv {
  stop-color: var(--svg-color--554a63, #554A63);
}

.wbe-qab5p {
  stop-color: var(--svg-color--50405f, #50405F);
}

.zi0bqjbqb {
  stop-color: var(--svg-color--554a63, #554A63);
  stop-opacity: 0;
}

</style>
