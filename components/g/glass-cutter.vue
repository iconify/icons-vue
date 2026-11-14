<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ftxufjbcj"/><path class="fu2wsrbps"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:glass-cutter" /></template>
<style>
.ftxufjbcj {
  d: path("M2.5 9H15v12.5H2.5Z");
}

.fu2wsrbps {
  d: path("M8 15.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm3.5-1.5l5.25-5.25m-1.005-1.116l3.889-3.889l2.121 2.121l-3.889 3.889ZM5.5 18.5l3-1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
