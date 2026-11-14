<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tb6jmu62v"/><path class="f_0grlbfp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:log-stack" /></template>
<style>
.f_0grlbfp {
  d: path("M8 8.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm0 7h.01m7.99 0h.01M12 8.5h.01");
}

.tb6jmu62v {
  d: path("M4 15.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm8 0a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
