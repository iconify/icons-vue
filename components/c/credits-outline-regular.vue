<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lh7nxd5dq"/><path class="ji-xh3b0v"/><path class="byqxsebzj"/><path class="p8a31xr4o"/><path class="lveb61hbp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:credits-outline-regular" /></template>
<style>
.byqxsebzj {
  d: path("M16 8h6");
}

.ji-xh3b0v {
  d: path("M8 10.5v3");
}

.lh7nxd5dq {
  d: path("M3 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

.lveb61hbp {
  d: path("M16 16h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p8a31xr4o {
  d: path("M16 12h6");
}

</style>
