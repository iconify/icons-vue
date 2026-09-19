<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="v2hbxebve"/><path class="ute2vob5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:easy-fire-tools" /></template>
<style>
.ute2vob5h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.906 33.228c-.248 2.407-.138 4.814-1.624 6.497h13.436c-1.753-1.873-1.863-4.195-2.185-6.497m3.381-18.007v11.225a1.887 1.887 0 0 0 1.887 1.887h.565m-8.636.001V15.88a2.64 2.64 0 0 1 2.641-2.641h0a5 5 0 0 1 .855.066m-5.707 5.029h10.376m-13.28 8.114a3.65 3.65 0 0 1-3.208 1.886a3.785 3.785 0 0 1-3.773-3.773v-2.453a3.774 3.774 0 1 1 7.547 0v1.32h-7.547");
}

.v2hbxebve {
  width: 36.884px;
  height: 24.954px;
  x: 5.558px;
  y: 8.275px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
}

</style>
