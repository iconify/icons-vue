<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="viay5lohm"/><path class="bnhtcjodd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lawn-scarifier" /></template>
<style>
.bnhtcjodd {
  d: path("M6.5 18a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm6.5-2l1.5 4l1.5-4l1.5 4l1.5-4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.viay5lohm {
  d: path("M6 10h14v6H6Zm1.5 0L4 3");
}

</style>
