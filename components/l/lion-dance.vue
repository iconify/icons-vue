<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="tc6rnfv-t"/><path class="pn5dh-bzk"/><path class="j0f5vuboa"/><path class="dtnqndrug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lion-dance" /></template>
<style>
.dtnqndrug {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 14.75h7a.75.75 0 0 1 .7 1c-.8 1.75-2.3 2.5-4.2 2.5s-3.4-.75-4.2-2.5a.75.75 0 0 1 .7-1m2.25 0v1.5m2.5-1.5v1.5");
}

.j0f5vuboa {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 12h.01m4.99 0h.01");
}

.pn5dh-bzk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 9.75c1.1-1.1 2.4-1.1 3.5 0m1.5 0c1.1-1.1 2.4-1.1 3.5 0");
}

.tc6rnfv-t {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6a2.3 2.3 0 0 1 4.11 1.34a2.3 2.3 0 0 1 2.55 3.5a2.3 2.3 0 0 1 0 4.32a2.3 2.3 0 0 1-2.55 3.5A2.3 2.3 0 0 1 12 20a2.3 2.3 0 0 1-4.11-1.34a2.3 2.3 0 0 1-2.55-3.5a2.3 2.3 0 0 1 0-4.32a2.3 2.3 0 0 1 2.55-3.5A2.3 2.3 0 0 1 12 6");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
