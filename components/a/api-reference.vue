<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2-td7fek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:api-reference" /></template>
<style>
.t2-td7fek {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6.5C10 5 7 4.5 2.5 5v13.5C7 18 10 18.5 12 20c2-1.5 5-2 9.5-1.5V5C17 4.5 14 5 12 6.5Zm0 0V20");
}

</style>
