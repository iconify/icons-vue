<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="aiy3u_f6a"/><path class="cw_0qobox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hand-heart-duocolor-round" /></template>
<style>
.aiy3u_f6a {
  stroke-opacity: 0.4;
  d: path("M12 4c-2-2-5 0-3 2l3 3l3-3c2-2-1-4-3-2");
}

.cw_0qobox {
  d: path("m4 16l3-3c.6-.6 1.2-1 2-1h3a2 2 0 1 1 0 4h-2m4-2l3-3a2.121 2.121 0 1 1 3 3l-5 5c-.64.64-1.36 1-2 1H8m-5-5l6 6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
