<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hm_57xx9s"/><path class="uas-qrbza"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dao-vote" /></template>
<style>
.hm_57xx9s {
  d: path("M7 11.5H5.5a2 2 0 0 0-2 2V19a2 2 0 0 0 2 2h13a2 2 0 0 0 2-2v-5.5a2 2 0 0 0-2-2H17m-10 0V4a1.5 1.5 0 0 1 1.5-1.5h7A1.5 1.5 0 0 1 17 4v7.5");
}

.uas-qrbza {
  d: path("m9.5 7l2 2l3-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
