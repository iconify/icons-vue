<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jv3wyodeg"/><path class="m94i2ibah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:design-token-colour" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jv3wyodeg {
  d: path("M12 3c5.5 0 9.5 4 9.5 8.5c0 3-2.5 4-4.5 3.5s-3.5 1-2.5 3s-.5 3-2.5 3c-5.5 0-9.5-4-9.5-9s4-9 9.5-9");
}

.m94i2ibah {
  d: path("m9.75 8.433l.665.384a1.5 1.5 0 0 1 .75 1.299v.768a1.5 1.5 0 0 1-.75 1.299l-.665.384a1.5 1.5 0 0 1-1.5 0l-.665-.384a1.5 1.5 0 0 1-.75-1.299v-.768a1.5 1.5 0 0 1 .75-1.299l.665-.384a1.5 1.5 0 0 1 1.5 0M13 8a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
