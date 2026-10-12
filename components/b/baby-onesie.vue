<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="a4dk5gpjn"/><path class="pwfcu_bse"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:baby-onesie" /></template>
<style>
.a4dk5gpjn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.49 3.76l1.77 1.23q.74.51 1.48 0l1.77-1.23q.74-.51 1.54-.11l2.9 1.45q.8.4 1.1 1.25l.9 2.55q.3.85-.53 1.2l-1.34.55q-.83.35-1.47-.29l-.22-.22q-.64-.64-.64.26v5.7q0 .9-.53 1.63l-1.69 2.29q-.53.73-1.43.73h-2.2q-.9 0-1.43-.73l-1.69-2.29q-.53-.73-.53-1.63v-5.7q0-.9-.64-.26l-.22.22q-.64.64-1.47.29l-1.34-.55q-.83-.35-.53-1.2l.9-2.55q.3-.85 1.1-1.25l2.9-1.45q.8-.4 1.54.11");
}

.pwfcu_bse {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 18h.01m2.99 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
