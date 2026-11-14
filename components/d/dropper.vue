<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4xa_4ska"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dropper" /></template>
<style>
.v4xa_4ska {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 11a8.5 8.5 0 0 1 17 0Zm0 0l6.25 5.5M20.5 11l-6.25 5.5M12 11v5.5m-2.5 0h5V21h-5Z");
}

</style>
