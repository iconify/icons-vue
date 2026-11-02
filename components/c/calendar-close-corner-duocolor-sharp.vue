<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l9ycfeb_j"/><path class="g4njagb-z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-close-corner-duocolor-sharp" /></template>
<style>
.g4njagb-z {
  d: path("M9 21H4V5h16v4M8 3v2m8-2v2M4 9h16");
}

.l9ycfeb_j {
  stroke-opacity: 0.4;
  d: path("m14 14l6 6m0-6l-6 6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
