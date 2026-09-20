<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="g077ugg2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fictionlog" /></template>
<style>
.g077ugg2v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.053 22.036v9.684M25.4 17.56c0 .706-.603 1.278-1.347 1.278s-1.347-.572-1.347-1.279s.603-1.279 1.347-1.279s1.347.573 1.347 1.28m10.249 12.32c-.664 1.099-1.912 1.84-3.343 1.84c-2.125 0-3.849-1.636-3.849-3.655V25.69c0-2.018 1.723-3.654 3.85-3.654c1.427 0 2.673.738 3.338 1.834m-23.294-1.834h5.389m-3.107 9.684V19.66c0-1.412 1.207-2.558 2.695-2.558c1.326 0 2.154.373 2.721 1.07");
}

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

</style>
