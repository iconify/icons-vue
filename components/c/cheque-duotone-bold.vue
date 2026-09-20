<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="t4wfbu4kp"/><path class="hgwdyn3fo"/><path class="odbxil02i"/><path class="ky4omnbla"/><path class="d3f-rpbhx"/><path class="yh3czw4qv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cheque-duotone-bold" /></template>
<style>
.d3f-rpbhx {
  d: path("M5 9h6");
}

.hgwdyn3fo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 9h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ky4omnbla {
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
}

.odbxil02i {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 15.5h6");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.yh3czw4qv {
  d: path("M13 15.5h6");
}

</style>
