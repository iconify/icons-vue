<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cn6n24byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gloves-leather-sharp" /></template>
<style>
.cn6n24byi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 15.5V12L5.6 9.35L4.578 8.253l2.12-2.12L7.72 7.23l.53.52v-5h8.5V15.5Zm3-12.75v4m2.5-4v4m-4.5 8.75h7.5l.21.98l.83 3.79l.21.98H7l.21-.98l.83-3.79l.21-.98z");
}

</style>
