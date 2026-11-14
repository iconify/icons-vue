<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lzmo99x5z"/><path class="g51arpxbx"/><path class="ghb8jkbdo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cesspit-emptying" /></template>
<style>
.g51arpxbx {
  d: path("M5.5 15.5h16v-4l-3-3h-1.25v7");
}

.ghb8jkbdo {
  d: path("M7 17.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm9 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-11-9H4A1.5 1.5 0 0 0 2.5 10v10");
}

.lzmo99x5z {
  d: path("M7 4.5h5.5a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
