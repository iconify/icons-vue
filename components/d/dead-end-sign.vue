<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="he9m0nb2n"/><path class="mvml0sbjb"/><path class="x2vewobfi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dead-end-sign" /></template>
<style>
.he9m0nb2n {
  d: path("M2 2h20v15H2Zm10 15v5");
}

.mvml0sbjb {
  fill: currentColor;
  d: path("M7 4.5h10V7H7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x2vewobfi {
  d: path("M12 7v7.5");
}

</style>
