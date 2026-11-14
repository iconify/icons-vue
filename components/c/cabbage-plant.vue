<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zwz9jvx6z"/><path class="oujraff_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cabbage-plant" /></template>
<style>
.oujraff_z {
  d: path("M7.5 13.75c2-5.25 4.5-7.75 9-9.5M12 15.5v3m0 0c-3 3-7 3-9 0c3-1.5 6.5-1.5 9 0Zm0 0c3 3 7 3 9 0c-3-1.5-6.5-1.5-9 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zwz9jvx6z {
  d: path("M5.5 9a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Z");
}

</style>
