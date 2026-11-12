<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hhmdn1v5b"/><path class="p4r49lbgj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ladle-line-duotone" /></template>
<style>
.hhmdn1v5b {
  d: path("M2 5.68421C2 3.64948 3.64948 2 5.68421 2C7.71894 2 9.36842 3.64948 9.36842 5.68421V15");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p4r49lbgj {
  d: path("M22.0002 14.5V15.6842C22.0002 19.1723 19.1726 22 15.6844 22C12.1963 22 9.36865 19.1723 9.36865 15.6842V14.6316M22.0002 14.5C22.0002 15.8807 19.0541 17 16.0002 17C12.9463 17 9.36865 16.0123 9.36865 14.6316M22.0002 14.5C22.0002 13.1193 19.0541 12 16.0002 12C12.9463 12 9.36865 13.2509 9.36865 14.6316");
}

</style>
