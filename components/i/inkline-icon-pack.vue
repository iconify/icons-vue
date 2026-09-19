<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pbtifib7o"/><path class="ixu4yebiy"/><circle class="mt1riyb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:inkline-icon-pack" /></template>
<style>
.ixu4yebiy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.855 21.832c-2.092.299-6.614 4.047-11.201 2.048m-1.55 5.224c1.544.946 3.18.836 3.18.836");
}

.mt1riyb6z {
  cx: 23.28px;
  cy: 42.453px;
  r: 0.75px;
  fill: currentColor;
}

.pbtifib7o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.196 4.797c1.494 3.138 4.732 9.315 0 12.154s-17.782 5.827-15.092 12.153c-3.935-2.79-6.027-11.506 0-14.693s13-5.38 15.092-9.613m-2.341 17.034c.897.747.847 1.992-.946 2.939s-9.912 2.54-9.912 9.364c0 4.134 2.988 6.226 2.988 6.226c-1.345-3.487 11.207-9.663 11.207-14.594c0-4.533-3.337-3.935-3.337-3.935");
}

</style>
