<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j9q5ub9pg"/><path class="erbb8objb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:butter-tub" /></template>
<style>
.erbb8objb {
  d: path("M3.5 9h7l3-3m-3 3v6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j9q5ub9pg {
  d: path("M3.5 15V9l3-3h7v6l-3 3ZM18 8h.5A1.5 1.5 0 0 1 20 9.5v4a1.5 1.5 0 0 1-1.5 1.5H18a1.5 1.5 0 0 1-1.5-1.5v-4A1.5 1.5 0 0 1 18 8M2.5 15h19c-1 3-3 3.5-5.5 3.5H8c-2.5 0-4.5-.5-5.5-3.5");
}

</style>
