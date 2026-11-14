<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="snrq6dj-a"/><path class="kzva48bte"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dried-beans-jar" /></template>
<style>
.kzva48bte {
  d: path("M10 12.75a2 1.25 0 1 0 4 0a2 1.25 0 1 0-4 0Zm-3.5 4.5a2 1.25 0 1 0 4 0a2 1.25 0 1 0-4 0Zm7 0a2 1.25 0 1 0 4 0a2 1.25 0 1 0-4 0Z");
}

.snrq6dj-a {
  d: path("M4.5 8.5h15a1 1 0 0 1 1 1v11a1 1 0 0 1-1 1h-15a1 1 0 0 1-1-1v-11a1 1 0 0 1 1-1Zm1-4.5h13v4.5h-13Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
