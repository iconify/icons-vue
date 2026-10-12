<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rk5433brp"/><path class="x1rumglbv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cairn" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rk5433brp {
  d: path("m3.69 18.08l.04-.04Q4.66 17 6.06 17h11.88q1.4 0 2.33 1.04l.04.04q.94 1.05 0 2.09l-.04.04q-.93 1.04-2.33 1.04H6.06q-1.4 0-2.33-1.04l-.04-.04q-.94-1.04 0-2.09m2.43-4.17l.17-.19q.87-.97 2.17-.97h6.33q1.3 0 2.17.97l.17.19q.87.97 0 1.93l-.17.19q-.87.97-2.17.97H8.46q-1.3 0-2.17-.97l-.17-.19q-.87-.96 0-1.93");
}

.x1rumglbv {
  d: path("m8.49 10.06l.21-.24Q9.44 9 10.54 9h2.67q1.1 0 1.84.82l.21.24q.74.82 0 1.63l-.21.24q-.74.82-1.84.82h-2.67q-1.1 0-1.84-.82l-.21-.24q-.74-.81 0-1.63m1.93-3.55l.24-.27q.66-.74 1.34-.74t1.34.74l.24.27q.67.74 0 1.48l-.24.27Q12.68 9 12 9t-1.34-.74l-.24-.27q-.67-.74 0-1.48");
}

</style>
