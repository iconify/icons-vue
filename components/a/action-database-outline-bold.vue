<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x3l7cj9iq"/><path class="nldbk4b3i"/><path class="ffs26fbkv"/><path class="mka94xbix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:action-database-outline-bold" /></template>
<style>
.ffs26fbkv {
  d: path("M12 17v4");
}

.mka94xbix {
  d: path("m9 19 3 3 3 -3");
}

.nldbk4b3i {
  d: path("M4 6a8 3 0 0 0 16 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.x3l7cj9iq {
  d: path("M4 6a8 3 0 0 1 16 0v8a8 3 0 0 1 -16 0Z");
}

</style>
