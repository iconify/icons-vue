<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bi7try_3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baba-ganoush" /></template>
<style>
.bi7try_3l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.18 19.498L12 19.5c-5 0-9-3.5-9-9h17.1M7.5 7C9 4.5 11 4.5 12 6.5s3 2 4.5-.5m3 9c2 1.5 2 6.5-2.5 6.5c-2.5 0-2.75-2.75-.5-3.75c1.5-.75 2-1.75 3-2.75Zm0 0l1.25-1.25");
}

</style>
