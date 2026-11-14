<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3eu_1xpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lightning-strike" /></template>
<style>
.z3eu_1xpk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.376 5.655L8.14 10.95A1.262 1.262 0 0 0 9.125 13h.574a1.5 1.5 0 0 1 1.429 1.955l-.253.795a.565.565 0 0 0 .972.533l4.053-4.862A1.171 1.171 0 0 0 15 9.5h-.469a1.5 1.5 0 0 1-1.434-1.941L13.5 6.25a.647.647 0 0 0-1.124-.595M3.5 21.25h17M5.5 17L7 18.5m7.5 0L16 17");
}

</style>
