<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rroz-ih4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-outdoor-furniture" /></template>
<style>
.rroz-ih4d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11a9.5 8 0 0 1 19 0ZM12 3v18.5M5.5 16h13M9 21.5h6M12 3l-4.5 8M12 3l4.5 8");
}

</style>
