<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rkn1xrbiw"/><path class="bpldrgrwn"/><path class="onkb4tbvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:database-lock" /></template>
<style>
.bpldrgrwn {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.5 3.6 2.75 8 2.75c.743 0 1.463-.036 2.147-.102m5.675-2.076q.177-.278.178-.572");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.onkb4tbvm {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.2 2.3 2.2 5.5 2.5m7.25 3.25h2.5A1.75 1.75 0 0 1 21 19.5v.25a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 15 19.75v-.25a1.75 1.75 0 0 1 1.75-1.75m-.25 0V16.5a1.5 1.5 0 0 1 3 0v1.25");
}

.rkn1xrbiw {
  d: path("M12.48 21.245q-.239.005-.48.005c-4.4 0-8-1.25-8-2.75v-13C4 4 7.6 2.75 12 2.75S20 4 20 5.5v7.155");
}

</style>
