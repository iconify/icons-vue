<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qq9ttib9q"/><path class="f7yj_-bhz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:experiment-stop" /></template>
<style>
.f7yj_-bhz {
  fill: currentColor;
  d: path("M15.5 15.5H21V21h-5.5Z");
}

.qq9ttib9q {
  d: path("M12.716 21H2.5l6-12V2.5H13V9l1.834 3.667M6.5 13h6.2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
