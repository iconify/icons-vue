<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="o8mly5boh"/><path class="t6s1qsbvk"/><path class="q-ycj7bec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cocoa-pod" /></template>
<style>
.o8mly5boh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 4l1.5-1.25M12 4c4.5 2 6.5 5.25 6.5 8.75s-2 6.5-6.5 8.5c-4.5-2-6.5-5-6.5-8.5S7.5 6 12 4");
}

.q-ycj7bec {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.25 15.5h.01m5.49 0h.01M12 18.25h.01");
}

.t6s1qsbvk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 7.25C10 8.5 9.75 9.5 9.75 10.5m3.75-3.25c.5 1.25.75 2.25.75 3.25M5.5 12.25h13");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
