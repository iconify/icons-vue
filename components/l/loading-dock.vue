<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="mm_dv_bqc"/><path class="if4bwodpo"/><rect class="o005c-bzt"/><circle class="fd2ud0b_q"/><circle class="jdahq6biz"/><path class="cd596su5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:loading-dock" /></template>
<style>
.cd596su5p {
  d: path("M11.75 21.25h9.5");
}

.fd2ud0b_q {
  cx: 17.25px;
  cy: 19px;
  r: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.if4bwodpo {
  d: path("M12.75 13.25L15 15");
}

.jdahq6biz {
  cx: 20px;
  cy: 19px;
  r: 1.25px;
}

.mm_dv_bqc {
  width: 9px;
  height: 8.5px;
  x: 2.75px;
  y: 12.75px;
  rx: 1px;
}

.o005c-bzt {
  width: 5.25px;
  height: 11.5px;
  x: 16px;
  y: 5px;
  rx: 1px;
}

</style>
