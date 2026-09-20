<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cia0y5byl"/><path class="ab5v244hw"/><path class="fa1bfob4c"/><path class="n3erp-b_d"/><path class="bwc3m7bel"/><path class="vhfgw5-us"/><path class="a-ogebbgz"/><path class="e2evtpg8i"/><path class="q4rhaacat"/><path class="hv2_9fjhy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:detour-duotone-thin" /></template>
<style>
.a-ogebbgz {
  d: path("M12 7v9");
}

.ab5v244hw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 7v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bwc3m7bel {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m20 13 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cia0y5byl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 16h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e2evtpg8i {
  d: path("M9.5 9.5 12 7l2.5 2.5");
}

.fa1bfob4c {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9.5 9.5 12 7l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hv2_9fjhy {
  d: path("m20 13 -4 4");
}

.n3erp-b_d {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 13 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q4rhaacat {
  d: path("m16 13 4 4");
}

.vhfgw5-us {
  d: path("M2 16h10");
}

</style>
