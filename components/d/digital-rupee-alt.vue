<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="cup5tmi8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:digital-rupee-alt" /></template>
<style>
.cup5tmi8n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.806 30.355a4.251 4.251 0 0 1-7.945-2.106v-2.763a4.251 4.251 0 0 1 8.502 0v1.381h-8.501M23.873 15.5h3.441c3.148 0 5.699 2.557 5.699 5.71s-2.551 5.712-5.698 5.712l5.698 5.578m-5.699-17h7.825m-11.266 5.739h11.266");
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
