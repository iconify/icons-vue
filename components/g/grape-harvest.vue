<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lm9tyksmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:grape-harvest" /></template>
<style>
.lm9tyksmo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15.5V20A1.5 1.5 0 0 0 4 21.5h16a1.5 1.5 0 0 0 1.5-1.5v-4.5m-19 3h19m-19-10a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm3 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM4 11a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm11.5-2.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm3 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM17 11a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM9 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm3 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-1.5 2.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

</style>
