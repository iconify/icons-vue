<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3ia6kbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bookshelf-sharp" /></template>
<style>
.p3ia6kbgq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 2.75h16v18.5H2.75V2.75zM2.75 12h18.5M7 5.75v3.5m3-3.5v3.5m2.75 0l2-3.5m-.75 9v3.5m3-3.5v3.5");
}

</style>
