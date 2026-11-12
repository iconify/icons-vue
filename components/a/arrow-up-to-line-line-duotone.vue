<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ah9s1bcom"/><path class="jzotxgntu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-up-to-line-line-duotone" /></template>
<style>
.ah9s1bcom {
  d: path("M4 3L20 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jzotxgntu {
  d: path("M12 21L12 8M8 12.375L12 8L16 12.375");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
