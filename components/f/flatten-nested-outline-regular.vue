<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xhii43btc"/><path class="icp673bbo"/><path class="ko0o6vb7i"/><path class="s4l_k6b-t"/><path class="nuugr4b2c"/><path class="e1kd5d-qm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:flatten-nested-outline-regular" /></template>
<style>
.e1kd5d-qm {
  d: path("M17 20h4");
}

.icp673bbo {
  d: path("M12 9v3");
}

.ko0o6vb7i {
  d: path("M5 16v-4h14v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nuugr4b2c {
  d: path("M10 20h4");
}

.s4l_k6b-t {
  d: path("M3 20h4");
}

.xhii43btc {
  d: path("M8 4a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

</style>
