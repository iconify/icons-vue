<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bckix3qhv"/><path class="aqtr1nzmx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cold-frame" /></template>
<style>
.aqtr1nzmx {
  d: path("M12 19.5v-4.25m0 .75c0-2.5-2-4-4.5-4c0 2.5 2 4 4.5 4Zm0-.75c0-2 1.75-3 3.75-3c0 2.25-1.5 3-3.75 3Z");
}

.bckix3qhv {
  d: path("M3.5 19.5v-14l17 5.5v8.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
