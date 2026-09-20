<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wrnic2b7h"/><path class="m0p17bc4l"/><path class="olxc00wjs"/><path class="m7goar83z"/><path class="z_j864liq"/><path class="be-du29wl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:goal-milestone-duotone-bold" /></template>
<style>
.be-du29wl {
  d: path("M12 2.5h5V6h-5");
}

.m0p17bc4l {
  fill: currentColor;
  d: path("M10 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.m7goar83z {
  d: path("M10 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.olxc00wjs {
  d: path("M6 15a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wrnic2b7h {
  fill: currentColor;
  d: path("M6 15a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.z_j864liq {
  d: path("M12 2v7");
}

</style>
