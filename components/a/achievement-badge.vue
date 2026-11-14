<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jqqdk0m7p"/><path class="sykahhbal"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:achievement-badge" /></template>
<style>
.jqqdk0m7p {
  d: path("M5 9.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0Z");
}

.sykahhbal {
  d: path("M9 15.75L7.5 21.5l2.5-1l1-4m4-.75l1.5 5.75l-2.5-1l-1-4M12 6l.75 2.25l2.5.25l-2 1.5l.75 2.25L12 11l-2 1.25l.75-2.25l-2-1.5l2.5-.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
