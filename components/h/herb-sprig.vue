<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jd0gicb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:herb-sprig" /></template>
<style>
.jd0gicb7e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21V9m0 0c-2-1.5-2-4 0-6c2 2 2 4.5 0 6Zm0 5c-2-3-5-4-7.5-3.5C5 13 8 15 12 14Zm0 0c2-3 5-4 7.5-3.5C19 13 16 15 12 14Z");
}

</style>
