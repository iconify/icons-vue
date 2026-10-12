<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkxsps1fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:earthworm-sharp" /></template>
<style>
.dkxsps1fu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13.25a5.25 5.25 0 0 1 10.5 0a2.25 2.25 0 0 0 4.5 0v-5h3v5a5.25 5.25 0 0 1-10.5 0a2.25 2.25 0 0 0-4.5 0a1.5 1.5 0 0 1-3 0ZM8 8.75v1.5m7.5 6v1.5m3-6H20m-17 9.5h18");
}

</style>
