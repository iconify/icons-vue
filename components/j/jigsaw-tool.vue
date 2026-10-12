<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cxvzjsrrl"/><path class="y9m4tsb8d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:jigsaw-tool" /></template>
<style>
.cxvzjsrrl {
  d: path("M5.5 5h11.25a3.5 3.5 0 0 1 3.5 3.5V14H3.75V6.75A1.75 1.75 0 0 1 5.5 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9m4tsb8d {
  d: path("M8.25 8h7.5a1.25 1.25 0 0 1 0 2.5h-7.5a1.25 1.25 0 0 1 0-2.5M6.5 14v3.25m-2.75 0H13M16.25 14v7.25");
}

</style>
