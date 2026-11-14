<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gcpc9_-ck"/><path class="ps0ebky0h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bus-priority-signal" /></template>
<style>
.gcpc9_-ck {
  d: path("M7.875 2h.25A4.375 4.375 0 0 1 12.5 6.375v11.25A4.375 4.375 0 0 1 8.125 22h-.25A4.375 4.375 0 0 1 3.5 17.625V6.375A4.375 4.375 0 0 1 7.875 2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ps0ebky0h {
  d: path("M6.5 6.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m0 5.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m0 5.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M16 7.5h2.75a2.25 2.25 0 0 1 0 4.5H16Zm0 4.5h3.25a2.25 2.25 0 0 1 0 4.5H16Z");
}

</style>
