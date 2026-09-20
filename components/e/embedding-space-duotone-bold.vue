<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gtlfk7rgu"/><path class="zi7f37b4e"/><path class="n7t0anb5n"/><path class="b5ic9acln"/><path class="n1soxcq3c"/><path class="y6kfzfgng"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:embedding-space-duotone-bold" /></template>
<style>
.b5ic9acln {
  d: path("m15 7 5 5 -8 8 -8 -8 5 -5");
}

.gtlfk7rgu {
  fill: currentColor;
  d: path("m15 7 5 5 -8 8 -8 -8 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.n1soxcq3c {
  d: path("M8 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.n7t0anb5n {
  fill: currentColor;
  d: path("M14 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

.y6kfzfgng {
  d: path("M14 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.zi7f37b4e {
  fill: currentColor;
  d: path("M8 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
