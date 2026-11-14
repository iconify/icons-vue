<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iwnnrs6eq"/><path class="xg45q1u9k"/><path class="t9mi4ob0q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hard-drive-download" /></template>
<style>
.iwnnrs6eq {
  d: path("M3 12h18v8H3Z");
}

.t9mi4ob0q {
  d: path("m10 8l2 2l2-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xg45q1u9k {
  d: path("m3.5 12.5l2.5-7a1.5 1.5 0 0 1 1.5-1h9a1.5 1.5 0 0 1 1.5 1l2.5 7M7 16h.01M10 16h.01M12 6v4");
}

</style>
