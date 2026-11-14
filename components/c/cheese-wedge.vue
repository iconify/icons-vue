<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ayycwrbdl"/><path class="jzfxgpbqx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cheese-wedge" /></template>
<style>
.ayycwrbdl {
  d: path("M3.5 17h17v-6l-17-4Z");
}

.jzfxgpbqx {
  d: path("M6.5 13a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm7.25.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
