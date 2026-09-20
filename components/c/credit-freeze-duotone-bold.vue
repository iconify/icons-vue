<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="t4wfbu4kp"/><path class="cyc9udv9l"/><path class="zz4qz5bzn"/><path class="ky4omnbla"/><path class="c1si20bso"/><path class="wihdixnjz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:credit-freeze-duotone-bold" /></template>
<style>
.c1si20bso {
  d: path("M10 9v6");
}

.cyc9udv9l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 9v6");
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

.wihdixnjz {
  d: path("M14 9v6");
}

.zz4qz5bzn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
