<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w0vrf3b7w"/><path class="uou25sbux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dark-web" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uou25sbux {
  d: path("M12 10c-2 1.75-3.25 3.5-3.25 5.5S10 19 12 19m0-9c2 1.75 3.25 3.5 3.25 5.5S14 19 12 19m0-9v9m0-14.5c.75-1.25 2-1.75 3.25-1.75");
}

.w0vrf3b7w {
  d: path("M12 4.5c-.5 2-1.25 3-2.75 4.25c-2.5 2-4.25 4-4.25 6.5a7 6 0 0 0 14 0c0-2.5-1.75-4.5-4.25-6.5C13.25 7.5 12.5 6.5 12 4.5");
}

</style>
