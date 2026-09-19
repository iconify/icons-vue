<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l-t2ahqvk"/><path class="nl2xplbhf"/><path class="rz_i5fbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:catima-alt" /></template>
<style>
.l-t2ahqvk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.6 12.7v18.7H9c-6-.8-6-18.1 0-18.7Zm-29.4 0l2-4.6l10.4 4.6h1.1l10.6-4.6l2.1 4.6Z");
}

.nl2xplbhf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.6 20.7l3.9 1.2l-5.2 18L9 31.4m4.6-11.1l2.8-2.6l2.8 2.6m7.1 0l2.8-2.6l2.8 2.6");
}

.rz_i5fbzm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.1 25.1c.6 2.3 3.6 1.5 3.6-.9c0 2.4 2.9 3.2 3.5.9");
}

</style>
