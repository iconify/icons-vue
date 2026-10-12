<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="dcato8bby"/><circle class="p7yvogb3i"/><path class="jx4kssztm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hot-plate" /></template>
<style>
.dcato8bby {
  width: 16.5px;
  height: 8px;
  x: 3.75px;
  y: 13.25px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jx4kssztm {
  d: path("M12.75 17.25h3.5m-11.5-7h14.5M8 7c-.9-1.25.9-2.5 0-3.75M12 7c-.9-1.25.9-2.5 0-3.75M16 7c-.9-1.25.9-2.5 0-3.75");
}

.p7yvogb3i {
  cx: 8px;
  cy: 17.25px;
  r: 1.75px;
}

</style>
