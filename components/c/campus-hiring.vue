<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ncyjf7bjy"/><path class="xxqj4qvfg"/><path class="hk57ajm5r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:campus-hiring" /></template>
<style>
.hk57ajm5r {
  d: path("M12 13.75v1.75h1.5");
}

.ncyjf7bjy {
  d: path("M6 21.5v-10L12 7l6 4.5v10ZM12 7V2m0 0l5 1.25l-5 1.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xxqj4qvfg {
  d: path("M8.75 15.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

</style>
