<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dzt371_db"/><path class="cj6dj02_r"/><path class="trp0jez5m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:coins-line-duotone" /></template>
<style>
.cj6dj02_r {
  d: path("M16 9C16 12.866 12.866 16 9 16C5.134 16 2 12.866 2 9C2 5.134 5.134 2 9 2C12.866 2 16 5.134 16 9Z");
}

.dzt371_db {
  d: path("M15.9365 8.06299C19.5274 8.54799 22.1546 11.6933 21.9925 15.3132C21.8304 18.9331 18.9326 21.8309 15.3127 21.993C11.6928 22.1551 8.5475 19.5279 8.0625 15.937");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.trp0jez5m {
  d: path("M9 6.5V11.5");
}

</style>
