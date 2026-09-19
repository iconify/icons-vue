<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="x5evqmbms"/><path class="nasacpb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-chat-alt" /></template>
<style>
.nasacpb4k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.916 13.575H9.51a2.62 2.62 0 0 0-2.622 2.621v24.753a1.049 1.049 0 0 0 1.79.742l5.91-5.91h16.328a2.62 2.62 0 0 0 2.62-2.62V16.196a2.62 2.62 0 0 0-2.62-2.621");
}

.x5evqmbms {
  width: 26.648px;
  height: 22.207px;
  x: 14.463px;
  y: 6px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.621px;
}

</style>
