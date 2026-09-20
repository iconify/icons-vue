<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pemn838wn"/><path class="ia4sldbfw"/><path class="uepfj3b0o"/><path class="lx6fvk9xv"/><path class="gku_y1i9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:insurance-broker-outline-bold" /></template>
<style>
.gku_y1i9j {
  d: path("M12 17.5V20");
}

.ia4sldbfw {
  d: path("M3 21a9 9 0 0 1 18 0");
}

.lx6fvk9xv {
  d: path("M8.5 17.5h7");
}

.pemn838wn {
  d: path("M9 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uepfj3b0o {
  d: path("M8.5 17.5a3.5 3.5 0 0 1 7 0");
}

</style>
