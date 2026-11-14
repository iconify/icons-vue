<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="skr-8wb1f"/><path class="q17s7lffv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:brain-tumour" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q17s7lffv {
  d: path("M4.75 12.5c2.75-1.25 5.75.25 8.75-1.5m-1-7.75c-.75 2 .75 3.5 0 5.5m3.75-3.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

.skr-8wb1f {
  d: path("M21.37 9.836c.153 1.068-.153 2.197-.87 2.914c.25 2.25-1.5 3.75-3.5 3.5c-1 1.5-3.5 2-5 1c-1.75 1-4.25.5-5-1c-2.25.25-4-1.5-3.5-3.5C2.25 11.5 2.25 9 3.75 8c0-1.75 1.5-2.75 3.25-2.25c.5-2 2.75-3 4.75-2.25c.564-.564 1.433-.823 2.309-.799m.691 15.049l.75 3.75");
}

</style>
