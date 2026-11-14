<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sduio8bfe"/><path class="qeqa7v_9s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:campfire-songs" /></template>
<style>
.qeqa7v_9s {
  d: path("M6.5 15.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm9 3.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4 0V14c0 2 2 2 2 4");
}

.sduio8bfe {
  d: path("M12.5 15.75a4.5 4.5 0 1 1-4.25-4.25a3.5 3.5 0 1 1 4.25 4.25Zm1.75-6L20.5 3.5m-2.25.25l2 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
