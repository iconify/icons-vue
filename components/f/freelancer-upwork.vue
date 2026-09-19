<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ome5678is"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:freelancer-upwork" /></template>
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

.ome5678is {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.043 22.04v6.909M12 18.355v6.651a4.044 4.044 0 0 0 4.033 4.033h0a4.04 4.04 0 0 0 4.03-4.033v-6.65m2.569-.017s2.222 10.655 8.54 10.474c2.51-.07 4.866-1.711 4.827-5.405c-.032-3.435-2.318-5.034-5.02-4.766c-7.268.724-6.749 19.496-6.749 19.496");
}

</style>
