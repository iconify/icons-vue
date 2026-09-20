<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGX9k6kIOO)" class="rgrbctb3k"/><path fill="url(#SVG7yJIwcFa)" class="ano1hxbxa"/><path class="bv_b60wgs"/><defs><linearGradient id="SVGX9k6kIOO" x1="4.871" x2="12.633" y1="10.417" y2="19.674" gradientUnits="userSpaceOnUse"><stop class="kop_snbmt"/><stop offset="1" class="y938d6b6p"/></linearGradient><linearGradient id="SVG7yJIwcFa" x1="6.691" x2="10.853" y1="9.974" y2="18.299" gradientUnits="userSpaceOnUse"><stop class="do0zb0t0h"/><stop offset="1" class="w1ksf3b0e"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:crowd" /></template>
<style>
.ano1hxbxa {
  d: path("m12.94 13.216l.405.135l.365.072a1.26 1.26 0 0 0-.766-.207zm1.333.657c-.262.207-.752.36-1.441.374c.801 1.207 2.535 1.806 4.115 1.806a4.053 4.053 0 1 0 0-8.106c-1.382 0-3.098 1.194-3.827 2.252c-.225.675.225 1.126.45 1.35c.45-.855 2.342-2.25 3.377-2.25a2.702 2.702 0 1 1 0 5.403c-.932 0-2.026-.243-2.674-.829");
}

.bv_b60wgs {
  fill: var(--svg-color--0b9ed9, #0b9ed9);
  d: path("M10.643 12a.9.9 0 1 0 0-1.801a.9.9 0 0 0 0 1.801m2.701 1.802a.9.9 0 1 0 0-1.801a.9.9 0 0 0 0 1.801");
}

.do0zb0t0h {
  stop-color: var(--svg-color--16c399, #16c399);
}

.ft5dv1b6b {
  fill: none;
}

.kop_snbmt {
  stop-color: var(--svg-color--1cd875, #1cd875);
}

.rgrbctb3k {
  d: path("M11.201 13.247c-.509-.153-1.049.203-1.432.576c-.64.622-1.77.878-2.729.878a2.703 2.703 0 1 1 2.387-3.962c.195-.44.527-.807.946-1.045a4.048 4.048 0 1 0-3.333 6.358c1.932 0 4.098-.891 4.503-2.701z");
}

.w1ksf3b0e {
  stop-color: var(--svg-color--0fadbe, #0fadbe);
}

.y938d6b6p {
  stop-color: var(--svg-color--17c693, #17c693);
}

</style>
