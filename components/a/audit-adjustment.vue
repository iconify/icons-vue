<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xczsvrbbz"/><path class="mvzd7xbzm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:audit-adjustment" /></template>
<style>
.mvzd7xbzm {
  d: path("m14.025 8.354l-.707 2.828l2.828-.707Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xczsvrbbz {
  d: path("M17.5 13.1V21h-15V6h9.2m-9.2 4h8.2m-8.2 4h7.2m3.7 0h2.3m.9 0h.9m-15 3.5h15m-12-1.75h6m2.525-7.396l4.596-4.597l2.122 2.122l-4.597 4.596Z");
}

</style>
