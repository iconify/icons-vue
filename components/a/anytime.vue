<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w4epm_s9z"/><path class="patw9upde"/><path class="s_dq-8aea"/><circle class="bum0ccbbh"/><path class="hmizetfju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:anytime" /></template>
<style>
.bum0ccbbh {
  cx: 22.166px;
  cy: 16.775px;
  r: 0.75px;
  fill: currentColor;
}

.hmizetfju {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.342 18.951l4.707 4.707m-8.899-3.445l5.284 5.284c.49.49 1.286.49 1.776 0l.267-.267m-6.794-2.62l1.865-1.865M10.943 38.212a2.512 2.512 0 1 1-3.552 3.553L6.235 40.61a2.512 2.512 0 1 1 3.553-3.553m2.931 2.931l-4.707-4.707m10.185-.771l-2.93-2.93a2.512 2.512 0 1 0-3.552 3.552m2.93 2.93l-4.707-4.707M42.411 8.503a2.512 2.512 0 0 1-4.2 2.44l-1.154-1.155a2.512 2.512 0 1 1 3.553-3.552l.577.577l-3.553 3.552");
}

.patw9upde {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.925 24.368l2.93 2.93a2.512 2.512 0 1 1-3.552 3.552l-2.93-2.93m12.742-9.19a2.512 2.512 0 1 1 3.553-3.552l2.93 2.93m-8.259-1.154l4.707 4.707");
}

.s_dq-8aea {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.667 15.178a2.512 2.512 0 1 1 3.553-3.552l2.93 2.93");
}

.w4epm_s9z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.856 27.299l2.398 2.398a2.51 2.51 0 0 1 0 3.552c-.49.49-1.134.736-1.777.736");
}

</style>
