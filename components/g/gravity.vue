<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mq93ag2kv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gravity" /></template>
<style>
.mq93ag2kv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 6.5h12l2 7.5H4Zm3.5 0V5a2.5 2.5 0 0 1 5 0v1.5M12 16.75v4.75M9.5 19l2.5 2.5l2.5-2.5");
}

</style>
