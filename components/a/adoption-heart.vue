<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uselc-4uc"/><path class="qg0i6bbll"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:adoption-heart" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qg0i6bbll {
  d: path("M12 14.25L8.1 10.4A2.6 2.6 0 0 1 12 7a2.6 2.6 0 0 1 3.9 3.4Z");
}

.uselc-4uc {
  d: path("M2.75 11.5h3.5l1 3.5c.5 1.5 2.25 2.5 4.75 2.5s4.25-1 4.75-2.5l1-3.5h3.5l-2 5.5c-1 3-4 4.25-7.25 4.25S5.75 20 4.75 17Zm9.25 6v3.75");
}

</style>
