<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yhebvhb6f"/><path class="c84pb3ebf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:highlighter-duocolor-sharp" /></template>
<style>
.c84pb3ebf {
  d: path("m7 11l7-7l6 6l-7 7z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yhebvhb6f {
  stroke-opacity: 0.4;
  d: path("m8 12l-5 5v3h5l4-4");
}

</style>
