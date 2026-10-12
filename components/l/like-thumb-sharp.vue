<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="cglpvermq"/><path class="wb0xzxbah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:like-thumb-sharp" /></template>
<style>
.cglpvermq {
  d: path("M8.3 19.43a8.75 8.75 0 1 0-4.23-4.23l-.67 4.35l-.213 1.281L4.4 20.5Z");
}

.wb0xzxbah {
  d: path("M9.75 16.5v-5l1.85-3.3l.472-.932l1.95.75l-.472.932l-.45 1.8h2.45l1.406.027l-.306 1.373l-.75 3.05l-.228.842l-.872.008ZM7.5 11.75v4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
