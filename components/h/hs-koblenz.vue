<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="yfe6ib2kq"/><path class="wh-s4m7ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hs-koblenz" /></template>
<style>
.wh-s4m7ao {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.118 21.094L9.52 28.19a1.742 1.742 0 0 1-2.504-1.567V7.5a2 2 0 0 1 2-2h14.298a2 2 0 0 1 2 2v11.682c0 .814-.464 1.556-1.196 1.912M8.213 32.77l14.597-7.098a1.742 1.742 0 0 1 2.504 1.567V40.5a2 2 0 0 1-2 2H9.016a2 2 0 0 1-2-2v-5.819c0-.814.465-1.556 1.197-1.912");
}

.yfe6ib2kq {
  width: 11.777px;
  height: 37px;
  x: 29.206px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

</style>
