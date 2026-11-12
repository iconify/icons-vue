<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="d30a-z5bu"/><path class="l6-4u2bgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:login-line-duotone" /></template>
<style>
.d30a-z5bu {
  d: path("M12 20C16.4183 20 20 16.4183 20 12C20 7.58172 16.4183 4 12 4");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l6-4u2bgq {
  stroke-linejoin: round;
  d: path("M4 12H14M11 15L14 12L11 9");
}

</style>
