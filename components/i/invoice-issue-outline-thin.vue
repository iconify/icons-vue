<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nreq_9ofo"/><path class="csyuhrrop"/><path class="pty_wsbvs"/><path class="k0x593b0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:invoice-issue-outline-thin" /></template>
<style>
.csyuhrrop {
  d: path("M5 14V3h14v11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k0x593b0b {
  d: path("M13.5 6.5 16 9l-2.5 2.5");
}

.nreq_9ofo {
  d: path("M2 11v10h20V11L12 21Z");
}

.pty_wsbvs {
  d: path("M8 9h8");
}

</style>
