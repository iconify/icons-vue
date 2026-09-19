<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rr0u6fb6h"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fine-lock" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.rr0u6fb6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 24h37M24 24v7.907h.002c.524-1.498 2.19-2.429 3.922-2.19s3.01 1.573 3.009 3.142c-.002 1.57-1.283 2.903-3.016 3.138c-1.732.235-3.397-.699-3.917-2.197v8.7m0-37v7.907h-.002c-.524-1.498-2.19-2.429-3.922-2.19s-3.01 1.573-3.009 3.142c.002 1.57 1.283 2.903 3.016 3.138c1.732.235 3.397-.699 3.917-2.197V24");
}

</style>
