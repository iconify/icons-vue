<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="eff5yibna"/><path class="od35zp28z"/><path class="xemloibsh"/><path class="b_fzcqbeu"/><path class="b58isb55w"/><path class="pq9ly31-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:joystick-duotone-bold" /></template>
<style>
.b_fzcqbeu {
  d: path("M5 20a7 7 0 0 1 14 0");
}

.b58isb55w {
  d: path("M12 6v7");
}

.eff5yibna {
  fill: currentColor;
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.od35zp28z {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 20a7 7 0 0 1 14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pq9ly31-r {
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xemloibsh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 6v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
