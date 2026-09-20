<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n48w5yb-p"/><path class="r7xk8o29f"/><path class="ra-gd-w0u"/><path class="cbhkvd6hc"/><path class="dwpnoob9i"/><path class="q0ladwbck"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:editor-split-outline-bold" /></template>
<style>
.cbhkvd6hc {
  d: path("M5 13h4");
}

.dwpnoob9i {
  d: path("M14 9h5");
}

.n48w5yb-p {
  d: path("M14 4h5a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h5");
}

.q0ladwbck {
  d: path("M14 13h4");
}

.r7xk8o29f {
  d: path("M12 4v16");
}

.ra-gd-w0u {
  d: path("M5 9h5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
