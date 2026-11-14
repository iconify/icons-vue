<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tbra3sb5b"/><path class="f3068hb6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heat-pack" /></template>
<style>
.f3068hb6c {
  d: path("M8.5 18.5c-1-1.5 1-3 0-4.5s1-3 0-4.25M12 18.5c-1-1.5 1-3 0-4.5s1-3 0-4.25m3.5 8.75c-1-1.5 1-3 0-4.5s1-3 0-4.25");
}

.tbra3sb5b {
  d: path("M4.5 3h15a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1h-15a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1Zm-1 4h17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
