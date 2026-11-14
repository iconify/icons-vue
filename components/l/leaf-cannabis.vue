<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_o3-u66w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leaf-cannabis" /></template>
<style>
.j_o3-u66w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 15.5L10.25 9L12 2.5L13.75 9Zm0 0l3.058-4.524l4.985-2.225l-3.057 4.523Zm0 0l-4.986-2.226l-3.057-4.523l4.985 2.225Zm0 0l3.418-.667l2.983 1.796l-3.417.666Zm0 0l-2.984 1.795l-3.417-.666l2.983-1.796Zm0 0v6");
}

</style>
