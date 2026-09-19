<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q8yl-8buz"/><path class="yw21qn6dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lyne" /></template>
<style>
.q8yl-8buz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.094 10.998l6.499 6.498l-6.499 6.499l-6.498-6.499zM24.098 11l6.498 6.499l-6.498 6.498l-6.499-6.498zm13.002-.007l6.497 6.498l-6.498 6.498l-6.498-6.498zM11.102 24l6.498 6.5l-6.498 6.498L4.603 30.5z");
}

.yw21qn6dh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.094 23.992l6.499 6.499l-6.499 6.498l-6.498-6.498zm13.003.003l6.498 6.498l-6.498 6.498l-6.499-6.498z");
}

</style>
