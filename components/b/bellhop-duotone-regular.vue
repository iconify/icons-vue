<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w_x4iohoz"/><path class="gg7gi8bfs"/><path class="b9bmegbpx"/><path class="uw5kuce7r"/><path class="lps9qspxb"/><path class="zdricccut"/><path class="hc853a05m"/><path class="c6hn90blm"/><path class="b_5ug6ank"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bellhop-duotone-regular" /></template>
<style>
.b_5ug6ank {
  d: path("M17 20.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.b9bmegbpx {
  fill: currentColor;
  d: path("M17 20.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.c6hn90blm {
  d: path("M8 20.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.gg7gi8bfs {
  fill: currentColor;
  d: path("M8 20.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hc853a05m {
  d: path("M7 13.5h13");
}

.lps9qspxb {
  d: path("M3 3h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uw5kuce7r {
  d: path("M3 3v18");
}

.w_x4iohoz {
  fill: currentColor;
  d: path("M7 18V9h13v9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zdricccut {
  d: path("M7 18V9h13v9Z");
}

</style>
