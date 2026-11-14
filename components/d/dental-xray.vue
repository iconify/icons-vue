<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o72zbacef"/><path class="kxe-tbbai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dental-xray" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kxe-tbbai {
  d: path("M9.5 5.5c1.25 0 1.5.75 2.5.75s1.25-.75 2.5-.75c1.5 0 2.25 1.25 2.25 3s-1 2.75-1.25 4.25L15 17c-.25 1.5-1.75 1.5-2 0l-.25-2.75a.781.781 0 0 0-1.5 0L11 17c-.25 1.5-1.75 1.5-2 0l-.5-4.25c-.25-1.5-1.25-2.5-1.25-4.25s.75-3 2.25-3");
}

.o72zbacef {
  d: path("M8.875 2.5h6.25A4.375 4.375 0 0 1 19.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-6.25A4.375 4.375 0 0 1 4.5 17.125V6.875A4.375 4.375 0 0 1 8.875 2.5");
}

</style>
