<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="a-37yhb7n"/><path class="mjllekbnz"/><path class="fu9iqf-ht"/><path class="g8yenp7wc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:brain-duotone-bold" /></template>
<style>
.a-37yhb7n {
  fill: currentColor;
  d: path("M11 4C7 4 5 6 5 8c-2 1 -2 4 0 5 0 3 2 7 6 7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fu9iqf-ht {
  d: path("M11 4C7 4 5 6 5 8c-2 1 -2 4 0 5 0 3 2 7 6 7Z");
}

.g8yenp7wc {
  d: path("M14 4c4 0 6 2 6 4 2 1 2 4 0 5 0 3 -2 7 -6 7Z");
}

.mjllekbnz {
  fill: currentColor;
  d: path("M14 4c4 0 6 2 6 4 2 1 2 4 0 5 0 3 -2 7 -6 7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
