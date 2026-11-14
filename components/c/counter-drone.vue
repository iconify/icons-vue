<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ax3ql6_fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:counter-drone" /></template>
<style>
.ax3ql6_fc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.4 9.5h1.1v1.1m-3.9 3.9H9.5v-1.1M12 7v1.1m0 7.8V17m-5-5h1.1m7.8 0H17m-5-9.5A2.25 2.25 0 1 1 12 7a2.25 2.25 0 1 1 0-4.5ZM12 17a2.25 2.25 0 1 1 0 4.5a2.25 2.25 0 1 1 0-4.5ZM4.75 9.75a2.25 2.25 0 1 1 0 4.5a2.25 2.25 0 1 1 0-4.5Zm14.5 0a2.25 2.25 0 1 1 0 4.5a2.25 2.25 0 1 1 0-4.5ZM3.5 3.5l17 17");
}

</style>
