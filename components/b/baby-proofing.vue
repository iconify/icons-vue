<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t70t7u1kq"/><path class="t5yu3c-fk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baby-proofing" /></template>
<style>
.t5yu3c-fk {
  d: path("M7.5 20.5v-6h4v6m3.5-3h6v4h-6Zm1.5 0v-1a1.5 1.5 0 0 1 3 0v1");
}

.t70t7u1kq {
  d: path("M12.244 20.5H3.5v-10L12 3.25l8.5 7.25v2.556");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
