<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kxbjlpbbj"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:exness" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.kxbjlpbbj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.734 28.561c-.988 1.677-2.853 2.806-4.99 2.806h0c-3.173 0-5.744-2.49-5.744-5.56v-3.615c0-3.07 2.571-5.559 5.744-5.559h0c3.172 0 5.744 2.49 5.744 5.56V24H11m26 7.367L25.512 16.634m11.488 0L25.512 31.366");
}

</style>
