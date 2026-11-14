<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1qgz2b9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bundle-offer" /></template>
<style>
.t1qgz2b9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8h18v4.5H3Zm1.5 4.5h15v9h-15ZM12 8v13.5M12 8c-1.5-4.5-6-4-4 0m4 0c1.5-4.5 6-4 4 0");
}

</style>
