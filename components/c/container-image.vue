<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy_gyvbyg"/><path class="hw360db2r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:container-image" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hw360db2r {
  d: path("m3 7l8 4.5L19 7m-8 4.5V20m5.625-4.125l.914-.492a1.5 1.5 0 0 1 1.422 0l.914.492a.994.994 0 0 1 0 1.75l-.914.492a1.5 1.5 0 0 1-1.422 0l-.914-.492a.994.994 0 0 1 0-1.75M15 19.5l3.25 1.75l3.25-1.75");
}

.oy_gyvbyg {
  d: path("M12.183 19.334L11 20l-8-4.5V7l8-4.5L19 7v5.421");
}

</style>
