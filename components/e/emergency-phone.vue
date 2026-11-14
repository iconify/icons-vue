<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yy2dh6jyr"/><path class="kj7m9j28k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:emergency-phone" /></template>
<style>
.kj7m9j28k {
  d: path("M12.5 12.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM4.75 16c0 3.5 1.75 5.5 4.25 5.5c2 0 3-.75 3.5-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yy2dh6jyr {
  d: path("M8.5 2.5h12v17h-12ZM3 5h3.5v11H3Zm8.5 1.5h6");
}

</style>
