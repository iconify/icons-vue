<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkk6g5bwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:community-officer" /></template>
<style>
.pkk6g5bwd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 8L4.5 4.75c4.5-3 10.5-3 15 0L17.25 8Zm1.5 0v2.5a3.75 3.75 0 0 0 7.5 0V8M4.5 21.5c0-2.5 3.25-4.25 7.5-4.25s7.5 1.75 7.5 4.25M12 5.25h.01");
}

</style>
