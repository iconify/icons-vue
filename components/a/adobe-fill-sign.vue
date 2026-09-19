<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b-78o_7cy"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:adobe-fill-sign" /></template>
<style>
.b-78o_7cy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.97 13.5l4.705 4.626L19.61 30.27l-6.098 1.34l1.682-6.071zM14.064 34.187c8.279 1.07 13.177-.646 15.272-4.443c.694-1.257-.76-3.033-2.47-.998c-2.277 2.707-.653 9.324 5.204 2.523c-1.156 3.473-.139 3.585 2.418 1.314");
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
