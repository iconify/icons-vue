<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k6fi9qmtq"/><path class="ozi-k-boi"/><path class="k_zt_ib1v"/><path class="njt4q9htw"/><path class="v33uslbhb"/><path class="uvdljpy6b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:balance-hide-outline-regular" /></template>
<style>
.k_zt_ib1v {
  d: path("M16.7 12.71a5 5 0 0 1 -9.4 0");
}

.k6fi9qmtq {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.njt4q9htw {
  d: path("m9 15 -2 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ozi-k-boi {
  d: path("M3 7h18");
}

.uvdljpy6b {
  d: path("m15 15 2 2");
}

.v33uslbhb {
  d: path("M12 16v2.5");
}

</style>
