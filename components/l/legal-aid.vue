<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="krbimdb8o"/><rect class="opwd1ab7b"/><path class="qvsb4-9gz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:legal-aid" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.krbimdb8o {
  d: path("M12 3v6.5m-3.75-5h7.5m-7.5 0L6.75 8a1.5 1.5 0 0 0 3 0Zm7.5 0L14.25 8a1.5 1.5 0 0 0 3 0Z");
}

.opwd1ab7b {
  width: 2.5px;
  height: 7.75px;
  x: 2.75px;
  y: 13.5px;
  rx: 1px;
}

.qvsb4-9gz {
  d: path("M5.25 14.5H8l3.5 1.5h2a1.25 1.25 0 0 1 0 2.5h-3M5.25 21H14l6-3.25a1.25 1.25 0 0 0-1.25-2.15l-3.25 1.15");
}

</style>
