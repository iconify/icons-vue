<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="o3pq64aer"/><path class="lia9jdrfo"/><path class="q4t0ntb4q"/><path class="eoxa-cb-h"/><path class="z67_1-j3c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:collage-duotone-bold" /></template>
<style>
.eoxa-cb-h {
  d: path("M9 9h11v11H9Z");
}

.lia9jdrfo {
  fill: currentColor;
  d: path("M9 9h11v11H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.o3pq64aer {
  fill: currentColor;
  d: path("M3 4h9v9H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.q4t0ntb4q {
  d: path("M3 4h9v9H3Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.z67_1-j3c {
  d: path("M14 3h7v4");
}

</style>
