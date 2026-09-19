<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vk_wn-l7r"/><path class="wy88ikbxc"/><path class="l5eaq7ben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:digilog-tv" /></template>
<style>
.l5eaq7ben {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.306 34.41c-6.192-7.562-5.082-18.713 2.48-24.905s18.713-5.083 24.905 2.48a17.7 17.7 0 0 1 .038 22.379");
}

.vk_wn-l7r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 18.372a4.824 4.824 0 0 1 4.828 4.827c0 2.658-2.159 4.828-4.828 4.828s-4.828-2.17-4.828-4.828A4.824 4.824 0 0 1 24 18.372m9.656 20.912V42.5H14.345v-3.215c0-11.257 19.31-11.257 19.31 0");
}

.wy88ikbxc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.728 29.594c-3.525-5.121-2.23-12.13 2.89-15.655c5.122-3.525 12.131-2.23 15.656 2.891a11.26 11.26 0 0 1-.106 12.915");
}

</style>
