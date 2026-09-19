<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="o8keylbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ctt" /></template>
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

.o8keylbww {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.389 16.889v12.175c0 1.13.897 2.046 2.003 2.046h.6m-2.603-10.845h2.103m4.266-3.376v12.175c0 1.13.897 2.046 2.003 2.046h.6m-2.603-10.845h2.103M21.122 29.05c-.69 1.232-1.99 2.061-3.479 2.061c-2.212 0-4.006-1.832-4.006-4.092v-2.66c0-2.26 1.794-4.093 4.006-4.093c1.486 0 2.783.827 3.475 2.054");
}

</style>
