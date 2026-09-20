<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ic_pehd5a"/><path class="ziznm1ama"/><path class="xob7qnbfo"/><path class="uk-flc9on"/><path class="jlfjgzbqx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cycling-outline-regular" /></template>
<style>
.ic_pehd5a {
  d: path("M3 17h18");
}

.jlfjgzbqx {
  d: path("M9 9h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uk-flc9on {
  d: path("M5 5h7");
}

.xob7qnbfo {
  d: path("M9 17V5");
}

.ziznm1ama {
  d: path("M14 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
