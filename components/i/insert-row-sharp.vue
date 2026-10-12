<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0qedubgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:insert-row-sharp" /></template>
<style>
.w0qedubgz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v11H2.75zm0 5.5h18.5M9 8.25v5.5m6-5.5v5.5m-3 2.75v4.75m-2.375-2.375h4.75");
}

</style>
