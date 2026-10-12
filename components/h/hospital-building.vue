<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ktrjq-byo"/><path class="avqihw1yz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hospital-building" /></template>
<style>
.avqihw1yz {
  d: path("M12 2.75v4.5M9.75 5h4.5m-8 7.5v2m0 2.5v2m11.5-6.5v2m0 2.5v2M12 12.5V14m-2 7.25v-4h4v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ktrjq-byo {
  width: 18.5px;
  height: 12.25px;
  x: 2.75px;
  y: 9px;
  rx: 1.5px;
}

</style>
