<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k6sl9b-sa"/><path class="lwji9o8wa"/><path class="stbqycbjw"/><path class="atoje4bsc"/><path class="e2r0vmbrh"/><path class="kpiqhd6nn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:basement-duotone-bold" /></template>
<style>
.atoje4bsc {
  d: path("M2 6h20");
}

.e2r0vmbrh {
  d: path("M4 6v5h5v4h5v4h6");
}

.k6sl9b-sa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 6h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kpiqhd6nn {
  d: path("M20 18.5V21");
}

.lwji9o8wa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 6v5h5v4h5v4h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.stbqycbjw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 18.5V21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
