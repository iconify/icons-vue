<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hv42-peji"/><path class="wt-palohp"/><path class="lbdj6gbfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:asterisk-linear" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hv42-peji {
  d: path("M12 4V20");
}

.lbdj6gbfo {
  d: path("M5.07178 16L18.9282 8");
}

.wt-palohp {
  d: path("M5.07178 8L18.9282 16");
}

</style>
