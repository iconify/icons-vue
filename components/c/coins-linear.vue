<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cj6dj02_r"/><path class="qgn4umtvb"/><path class="trp0jez5m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:coins-linear" /></template>
<style>
.cj6dj02_r {
  d: path("M16 9C16 12.866 12.866 16 9 16C5.134 16 2 12.866 2 9C2 5.134 5.134 2 9 2C12.866 2 16 5.134 16 9Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qgn4umtvb {
  d: path("M15.9375 8.06299C19.5284 8.54799 22.1556 11.6933 21.9935 15.3132C21.8314 18.9331 18.9336 21.8309 15.3137 21.993C11.6938 22.1551 8.54848 19.5279 8.06348 15.937");
}

.trp0jez5m {
  d: path("M9 6.5V11.5");
}

</style>
