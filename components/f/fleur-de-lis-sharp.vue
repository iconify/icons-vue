<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5hpafwzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fleur-de-lis-sharp" /></template>
<style>
.m5hpafwzr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75c1.5 2 2.25 4.25 2.25 6.5c0 2-1 3.25-2.25 4.75c-1.25-1.5-2.25-2.75-2.25-4.75c0-2.25.75-4.5 2.25-6.5ZM8.75 14c-.75-2.25-1.5-4-3-4.75C4.5 8.6 3 9.25 3 10.75V13l2-1m10.25 2c.75-2.25 1.5-4 3-4.75c1.25-.65 2.75 0 2.75 1.5V13l-2-1M8 14h8v2H8zm4 2v4");
}

</style>
