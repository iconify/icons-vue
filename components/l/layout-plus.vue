<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jh4-22bkf"/><path class="fu2exubeu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:layout-plus" /></template>
<style>
.fu2exubeu {
  d: path("M3.5 7.5L12 12l8.5-4.5M12 12v9M3.5 9h17M9 9v11.5m9-5.5v6m-3-3h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jh4-22bkf {
  d: path("M13.373 20.273L12 21l-8.5-4.5v-9L12 3l8.5 4.5v6.265");
}

</style>
