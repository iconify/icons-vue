<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nreq_9ofo"/><path class="csyuhrrop"/><path class="dlkpyyv9b"/><path class="e8hevq1kc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:invoice-reminder-outline-thin" /></template>
<style>
.csyuhrrop {
  d: path("M5 14V3h14v11");
}

.dlkpyyv9b {
  d: path("M9 6v6");
}

.e8hevq1kc {
  d: path("M9 7h5v4H9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nreq_9ofo {
  d: path("M2 11v10h20V11L12 21Z");
}

</style>
