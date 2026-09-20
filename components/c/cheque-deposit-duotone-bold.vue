<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="t4wfbu4kp"/><path class="hgwdyn3fo"/><path class="os1f3nb5t"/><path class="l0s0v0b2h"/><path class="ky4omnbla"/><path class="d3f-rpbhx"/><path class="hokxmxb-u"/><path class="xl1fc1yvu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cheque-deposit-duotone-bold" /></template>
<style>
.d3f-rpbhx {
  d: path("M5 9h6");
}

.hgwdyn3fo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 9h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hokxmxb-u {
  d: path("M13 9v6");
}

.ky4omnbla {
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
}

.l0s0v0b2h {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10.5 12.5 13 15l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.os1f3nb5t {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 9v6");
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

.xl1fc1yvu {
  d: path("M10.5 12.5 13 15l2.5 -2.5");
}

</style>
