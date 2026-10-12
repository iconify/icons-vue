<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ipvd7kbpm"/><rect class="qllgkn6uk"/><path class="aps6b7b6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bunsen-flame-test" /></template>
<style>
.aps6b7b6j {
  d: path("M13.75 15.75h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ipvd7kbpm {
  d: path("M12 3c2.25 2.1 3.25 3.8 3.25 5.4a3.25 3.25 0 0 1-6.5 0c0-1.6 1-3.3 3.25-5.4m-1.75 15.25V15a1 1 0 0 1 1-1h1.5a1 1 0 0 1 1 1v3.25");
}

.qllgkn6uk {
  width: 12.5px;
  height: 3px;
  x: 5.75px;
  y: 18.25px;
  rx: 1.5px;
}

</style>
