<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j77vy-dxl"/><path class="nrhqa1b-t"/><path class="ak_539bla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:huawei-gamebox" /></template>
<style>
.ak_539bla {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.722 25.11h8.336l-4.168 7.497Z");
}

.j77vy-dxl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.889 12.97l-4.168 6.937h8.336Z");
}

.nrhqa1b-t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.091 18.788C13.114 3.334 34.507 4.18 38.297 17.78l4.979 17.876c1.198 4.3-2.648 5.914-5.79 4.168c-4.134-2.297-5.594-3.133-9.008-2.574c-1.71.28-4.935 1.09-8.057.224c-3.1-.86-6.758.285-10.154 2.462c-2.867 1.836-6.617-.245-5.595-4.169Z");
}

</style>
