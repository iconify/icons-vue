<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5_zperoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dry-lightning-sharp" /></template>
<style>
.v5_zperoq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.47 3.16l-4.94 7.18l-.28.41H9.5l.05.5l.4 4l.05.5l.32-.38l6.36-7.49l.32-.38h-4l.3-.4l2.9-3.95l.3-.4h-3.75zM2.75 17.25h18.5m-5.75 0l-1.25 1.5l1.5 1.5l-.75 1");
}

</style>
