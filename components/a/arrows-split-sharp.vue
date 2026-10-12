<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wosubxdan"/><path class="fca-dbchs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arrows-split-sharp" /></template>
<style>
.fca-dbchs {
  d: path("M5.75 9.75v-4h4m4.5 0h4v4");
}

.wosubxdan {
  d: path("M12 20.25V12L5.75 5.75M12 12l6.25-6.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
