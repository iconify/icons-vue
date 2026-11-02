<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ffbyqdb3a"/><path class="tzub2ih4h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:incognito-duocolor-round" /></template>
<style>
.ffbyqdb3a {
  stroke-opacity: 0.4;
  d: path("M4 17a3 3 0 1 0 6 0a3 3 0 0 0-6 0m10 0a3 3 0 1 0 6 0a3 3 0 0 0-6 0m-4 0a2 2 0 1 1 4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tzub2ih4h {
  d: path("m6 10l1-3c.597-1.792 2.208-3 4-3h2c1.792 0 3.403 1.208 4 3l1 3M3 10h18");
}

</style>
