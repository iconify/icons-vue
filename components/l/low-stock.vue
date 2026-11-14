<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tkb58bblb"/><path class="ba6gx5n6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:low-stock" /></template>
<style>
.ba6gx5n6j {
  d: path("m3.5 7l8.5 4.5L20.5 7M12 11.5v2.75m6 .75v3m0 3h.01");
}

.tkb58bblb {
  d: path("M12 2.5L20.5 7v5.25H14a2 2 0 0 0-2 2v7.25L3.5 17V7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
