<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9wdj360u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:coat-stand-sharp" /></template>
<style>
.d9wdj360u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 7V2.75h5.5V7h2.5v1.5H6.75V7h.75ZM12 8.5v12.75m-4 0h8M12 14l-3.5-2.25M12 14l3.5-2.25");
}

</style>
