<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qn-h03e3f"/><path class="e5vwh4bej"/><path class="kll7jabfs"/><path class="crv4i00bu"/><path class="wy8w_b5cr"/><path class="nzwwf5-_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:loss-duotone-bold" /></template>
<style>
.crv4i00bu {
  d: path("M4 3v18");
}

.e5vwh4bej {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 21h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kll7jabfs {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m6 5 6 6 3 3h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nzwwf5-_s {
  d: path("m6 5 6 6 3 3h5");
}

.qn-h03e3f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wy8w_b5cr {
  d: path("M4 21h18");
}

</style>
