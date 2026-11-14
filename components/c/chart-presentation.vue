<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aa65nebhk"/><path class="t-9y7ebua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-presentation" /></template>
<style>
.aa65nebhk {
  d: path("M4.5 4h15v9.5h-15ZM12 2v2m-3.5 9.5l-2 8m9-8l2 8m-5.5-8v8");
}

.t-9y7ebua {
  d: path("m8 11l2.5-3L13 9.5l3-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
