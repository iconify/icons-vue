<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="t4wfbu4kp"/><path class="y5z2jdb_k"/><path class="k6qg3p5lb"/><path class="ky4omnbla"/><path class="vrzboac1q"/><path class="ipav-zhpr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:balance-sheet-duotone-bold" /></template>
<style>
.ipav-zhpr {
  d: path("M14.5 8.5v7");
}

.k6qg3p5lb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14.5 8.5v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ky4omnbla {
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t4wfbu4kp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vrzboac1q {
  d: path("M9.5 8.5v7");
}

.y5z2jdb_k {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.5 8.5v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
