<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e7tb_4bvz"/><path class="rt77hvblu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:adhesive-bandage" /></template>
<style>
.e7tb_4bvz {
  d: path("M3.868 15.182L15.182 3.868a1.5 1.5 0 0 1 2.121 0l2.829 2.829a1.5 1.5 0 0 1 0 2.121L8.818 20.132a1.5 1.5 0 0 1-2.121 0l-2.829-2.829a1.5 1.5 0 0 1 0-2.121Z");
}

.rt77hvblu {
  d: path("M7.05 12L12 7.05L16.95 12L12 16.95Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
