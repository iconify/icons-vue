<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_8k-dbju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blood-pressure-cuff" /></template>
<style>
.y_8k-dbju {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3h13v8h-13Zm15 10.5c2 0 3.5 2.25 3.5 4.25c0 2.15-1.5 3.75-3.5 3.75S14 19.9 14 17.75c0-2 1.5-4.25 3.5-4.25ZM6.5 3v8M9 11c0 4.5 1.5 6.5 5 6.75m3.5-4.25v-2");
}

</style>
