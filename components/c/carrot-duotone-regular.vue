<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qa18rpbeu"/><path class="gc9tgz9ql"/><path class="a1pqz1blq"/><path class="jlpnm02dj"/><path class="z9owi-ayh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:carrot-duotone-regular" /></template>
<style>
.a1pqz1blq {
  d: path("M9 8 5 4");
}

.gc9tgz9ql {
  d: path("M9 8h6c0 5 -2 11 -3 13 -1 -2 -3 -8 -3 -13");
}

.jlpnm02dj {
  d: path("M12 8V3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qa18rpbeu {
  fill: currentColor;
  d: path("M9 8h6c0 5 -2 11 -3 13 -1 -2 -3 -8 -3 -13");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.z9owi-ayh {
  d: path("m15 8 4 -4");
}

</style>
