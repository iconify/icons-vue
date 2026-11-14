<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="giljqrbhr"/><path class="r9dmfcbxm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:alphabet-blocks" /></template>
<style>
.giljqrbhr {
  d: path("M5.625 12h3.25a2.625 2.625 0 0 1 2.625 2.625v3.25A2.625 2.625 0 0 1 8.875 20.5h-3.25A2.625 2.625 0 0 1 3 17.875v-3.25A2.625 2.625 0 0 1 5.625 12m9.5 0h3.25A2.625 2.625 0 0 1 21 14.625v3.25a2.625 2.625 0 0 1-2.625 2.625h-3.25a2.625 2.625 0 0 1-2.625-2.625v-3.25A2.625 2.625 0 0 1 15.125 12m-4.75-9h3.25a2.625 2.625 0 0 1 2.625 2.625v3.25a2.625 2.625 0 0 1-2.625 2.625h-3.25A2.625 2.625 0 0 1 7.75 8.875v-3.25A2.625 2.625 0 0 1 10.375 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r9dmfcbxm {
  d: path("m5.5 18l1.75-3.25L9 18m6.5-3.5V18M12 5.5h2L12 8h2");
}

</style>
