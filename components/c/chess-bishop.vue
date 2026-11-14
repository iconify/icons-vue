<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2lq90buj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chess-bishop" /></template>
<style>
.i2lq90buj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5c3 2 4.5 4.5 4.5 7c0 2-1 3.5-2.5 4h-4c-1.5-.5-2.5-2-2.5-4c0-2.5 1.5-5 4.5-7Zm-2 11L8.5 19m5.5-4.5l1.5 4.5m-10 0h13v2.5h-13Zm9.25-12.75l-3.5 3.5");
}

</style>
