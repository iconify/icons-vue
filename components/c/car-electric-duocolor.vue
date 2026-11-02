<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qa8w92b3c"/><path class="cngxt-90p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:car-electric-duocolor" /></template>
<style>
.cngxt-90p {
  d: path("m13 8l-3 3h4l-3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qa8w92b3c {
  stroke-opacity: 0.4;
  d: path("M12 18H6a2 2 0 0 1-2-2v-6l2-4c.613-1.226 1.387-2 2-2h8c.613 0 1.387.774 2 2l2 4v6a2 2 0 0 1-2 2zm-6 0h2v2H6Zm10 0h2v2h-2ZM3 10h1m16 0h1");
}

</style>
