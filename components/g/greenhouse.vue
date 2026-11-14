<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jn_iudbdt"/><path class="a492tdq6e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:greenhouse" /></template>
<style>
.a492tdq6e {
  d: path("M12 17.5c0-2.25-1.75-3.5-3.5-3.5c0 2 1.5 3.5 3.5 3.5m0-1c0-2.25 1.75-3.25 3.5-3.25c0 2-1.5 3.25-3.5 3.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jn_iudbdt {
  d: path("m4.422 9.714l5.875-5.011a2.625 2.625 0 0 1 3.406 0l5.875 5.011a2.63 2.63 0 0 1 .922 1.997v6.164a2.625 2.625 0 0 1-2.625 2.625H6.125A2.625 2.625 0 0 1 3.5 17.875v-6.164a2.63 2.63 0 0 1 .922-1.997M3.5 10.5h17M12 3.25v7.25m0 10V16");
}

</style>
