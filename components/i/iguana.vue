<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="wwglv-ihb"/><path class="l91ghxb2c"/><path class="qvx_uacff"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:iguana" /></template>
<style>
.l91ghxb2c {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.5 10l1-2l1 2l1-2l1 2l1-2l1 2.4m-5 5.1l-.5 3m4.5-3l.75 3m2-5.25c1.5 1 2 2.5 1.75 4.25c-.25 1.5-1.25 2.75-2.75 3.25");
}

.qvx_uacff {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 10.75h.01");
}

.wwglv-ihb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11c0-1 .75-1.75 1.75-1.9l3.5-.35c1.25-.15 2.5.35 3.25 1.25h4.25c2 0 3.5 1.5 3.5 3.25c0 1.25-1 2.25-2.25 2.25h-6l-1.5 2.25L8.25 15c-1.5-.25-2.75-1.5-4.35-2.4c-.55-.3-.9-.9-.9-1.6");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
