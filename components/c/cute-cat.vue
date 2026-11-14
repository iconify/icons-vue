<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dc0k_r-4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cute-cat" /></template>
<style>
.dc0k_r-4y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5 9l.5-5.5l4.5 3a8 8 0 0 1 4 0l4.5-3L19 9A8 8 0 1 1 5 9Zm4 3h.01M15 12h.01M12 15h.01");
}

</style>
