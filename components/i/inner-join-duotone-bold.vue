<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kodz2yb5m"/><path class="nemmfcl4b"/><path class="ygpel9b0x"/><path class="ewesysbte"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:inner-join-duotone-bold" /></template>
<style>
.ewesysbte {
  d: path("M12 20.37a8.5 8.5 0 0 1 0 -16.74");
}

.kodz2yb5m {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 3.63a8.5 8.5 0 0 1 0 16.74");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nemmfcl4b {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 20.37a8.5 8.5 0 0 1 0 -16.74");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ygpel9b0x {
  d: path("M12 3.63a8.5 8.5 0 0 1 0 16.74");
}

</style>
