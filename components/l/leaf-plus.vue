<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4yxq3gwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leaf-plus" /></template>
<style>
.x4yxq3gwc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.168 16.764A13.5 13.5 0 0 1 5.5 18.5C4.5 10 10 3 19.5 3c0 3.621-.944 6.734-2.529 9.2m-1.774 2.232a13 13 0 0 1-.815.769M3 21l9.5-9.5M18 15v6m-3-3h6");
}

</style>
