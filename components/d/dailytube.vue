<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="atoqg3dji"/><path class="epqkxbccl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dailytube" /></template>
<style>
.atoqg3dji {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.12 5.5H8.38v37h12.74A18.5 18.5 0 0 0 39.62 24a18.5 18.5 0 0 0-18.5-18.5");
}

.epqkxbccl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.073 24l-9.355-7.626v15.252zM8.381 5.5l13.337 10.874M8.381 42.5l13.337-10.874M31.073 24l2.56 2.087c2.7 1.964 3.836 7.39.586 10.976");
}

</style>
