<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucs-3xbnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crutches-sharp" /></template>
<style>
.ucs-3xbnj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 2.75h7.5v2.5h-7.5zm1 2.5L11 15.5h2l1.75-10.25M12 15.5v5.75m-2.1-10.5h4.2");
}

</style>
