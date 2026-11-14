<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="su47abe3x"/><path class="bc9tdhbry"/><path class="rj2amhbku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:database-connection" /></template>
<style>
.bc9tdhbry {
  d: path("M2.5 4.5v6a4.5 1.75 0 0 0 9 0v-6m1 9a4.5 1.75 0 1 0 9 0a4.5 1.75 0 1 0-9 0Z");
}

.rj2amhbku {
  d: path("M12.5 13.5v6a4.5 1.75 0 0 0 9 0v-6M7 12.25V17h5.5");
}

.su47abe3x {
  d: path("M2.5 4.5a4.5 1.75 0 1 0 9 0a4.5 1.75 0 1 0-9 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
