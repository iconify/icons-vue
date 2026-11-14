<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usn736b3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:editorial-calendar" /></template>
<style>
.usn736b3f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.2 21H3.5V4.5h17v7.6M8 2.5v4m8-4v4m-12.5 3h17m-5.5 12v-2l4.5-4.5l2 2l-4.5 4.5Z");
}

</style>
