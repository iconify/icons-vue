<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ve52kfbdk"/><path class="kmr3t9bya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:frost-fleece" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kmr3t9bya {
  d: path("M12 14.5c-2 0-3.25-1.5-3.5-3.75c2 0 3.25 1.5 3.5 3.75m0 0c2 0 3.25-1.5 3.5-3.75c-2 0-3.25 1.5-3.5 3.75");
}

.ve52kfbdk {
  d: path("M3.5 20C4 14 6 6.5 12 6c6 .5 8 8 8.5 14q-2.125-1.5-4.25 0q-2.125-1.5-4.25 0q-2.125-1.5-4.25 0q-2.125-1.5-4.25 0m8.5 0v-7");
}

</style>
