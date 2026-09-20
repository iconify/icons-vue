<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r3uz_wvor"/><path class="vvv_0v-7b"/><path class="auc4o2swl"/><path class="bu35rpbki"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hammock-outline-thin" /></template>
<style>
.auc4o2swl {
  d: path("M4 8c0 8 16 8 16 0");
}

.bu35rpbki {
  d: path("M4 12c0 7 16 7 16 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r3uz_wvor {
  d: path("M4 6v15");
}

.vvv_0v-7b {
  d: path("M20 6v15");
}

</style>
