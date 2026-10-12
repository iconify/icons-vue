<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="dnp2npbye"/><path class="ibe9b_vxd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:billing" /></template>
<style>
.dnp2npbye {
  width: 14.5px;
  height: 18.5px;
  x: 4.75px;
  y: 2.75px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ibe9b_vxd {
  d: path("M8.25 6.5h7.5m-2.04 5.29c-.25-.62-.93-1.08-1.71-1.08c-.99 0-1.71.56-1.71 1.33c0 1.77 3.56.99 3.56 2.88c0 .81-.78 1.36-1.86 1.36c-.84 0-1.55-.46-1.86-1.08M12 9.63v1.08m0 5.58v1.08");
}

</style>
