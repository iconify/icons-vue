<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="r1596klyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iq-option" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r1596klyr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.578 20.565c1.531 0 2.772 1.263 2.772 2.822v9.589c0 1.558-1.24 2.821-2.772 2.821h0c-1.531 0-2.772-1.263-2.772-2.821v-9.59c0-1.558 1.241-2.82 2.772-2.82m8.704-5.086c1.53 0 2.772 1.263 2.772 2.821v14.624c0 1.558-1.241 2.822-2.772 2.822h0c-1.531 0-2.773-1.264-2.773-2.822V18.301c0-1.558 1.242-2.821 2.773-2.821m8.728-4.61c1.531 0 2.773 1.264 2.773 2.822v19.2c0 1.559-1.242 2.822-2.773 2.822h0c-1.53 0-2.772-1.263-2.772-2.822v-19.2c0-1.558 1.241-2.821 2.772-2.821");
}

</style>
