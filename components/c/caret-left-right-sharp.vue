<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tsq9gabcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:caret-left-right-sharp" /></template>
<style>
.tsq9gabcf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.18 11.24l5.14-4.23l.93-.76v11.5l-.93-.76l-5.14-4.23l-.93-.76zm15.64 0l-5.14-4.23l-.93-.76v11.5l.93-.76l5.14-4.23l.93-.76z");
}

</style>
