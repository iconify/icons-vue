<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="pu96vwrwz"/><path class="nj780bc-x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:le-xiang-kuai-you" /></template>
<style>
.nj780bc-x {
  d: path("m32.628 27.28l-3.363 2.632l2.636 3.385m-14.064-7.098v8.18m4.065-4.09h-8.13");
}

.pu96vwrwz {
  d: path("M27.798 18.169h6.286c4.543 0 8.2 3.657 8.2 8.2v7.93a8.18 8.18 0 0 1-8.2 8.201H13.916a8.183 8.183 0 0 1-8.2-8.2v-7.931c0-4.543 3.657-8.2 8.2-8.2l8.518-.001l1.19-5.649l-6.585.573L23.85 5.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
