<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e2v7jqb9u"/><g class="y9tr6bcfx"><path class="qsl7tcbco"/><path class="a52tmrx7n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:asphalt-9" /></template>
<style>
.a52tmrx7n {
  d: path("M15.432 28.837v3.089l8.519 4.258l8.617-4.078v-9.314");
}

.e2v7jqb9u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.345 4.5v31.245L23.95 43.5l15.704-7.472V4.5z");
}

.qsl7tcbco {
  d: path("M15.432 11.816h17.136v10.977H15.432z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
