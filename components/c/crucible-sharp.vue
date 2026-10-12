<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_c1nybyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crucible-sharp" /></template>
<style>
.v_c1nybyq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 9.75h10l-.29 1.47l-1.67 8.56l-.29 1.47h-7l-.29-1.47l-1.67-8.56l-.29-1.47zm-2.25-3h13a6.5 3.5 0 0 0-13 0Z");
}

</style>
