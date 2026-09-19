<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d66aksb9k"/><path class="o7-8gcc3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ks-one" /></template>
<style>
.d66aksb9k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.378 38.052c-7.728 0-13.993-6.265-13.993-13.994s6.265-13.993 13.993-13.993c3.264 0 6.267 1.117 8.647 2.99");
}

.o7-8gcc3o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.019 3.404q.333 0 .663.01C32.75 3.764 41.615 12.847 41.615 24c0 11.375-9.221 20.596-20.596 20.596c-5.167 0-9.89-1.903-13.506-5.046");
}

</style>
