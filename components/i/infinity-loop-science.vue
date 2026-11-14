<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz-yx74bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:infinity-loop-science" /></template>
<style>
.fz-yx74bj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12c-3-6.5-9.5-6.5-9.5 0S9 18.5 12 12m0 0c3-6.5 9.5-6.5 9.5 0S15 18.5 12 12");
}

</style>
