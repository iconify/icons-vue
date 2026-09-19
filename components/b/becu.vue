<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o0dy6obyr"/><path class="iitj9jbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:becu" /></template>
<style>
.iitj9jbov {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.544 24a4.75 4.75 0 1 1 0 9.5h-7.838v-19h7.838a4.75 4.75 0 0 1 0 9.5m0 0h-7.838");
}

.o0dy6obyr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.78 5.951h28.44a4 4 0 0 1 4 4v20.89c0 6.19-5.017 11.208-11.207 11.208H9.78a4 4 0 0 1-4-4V9.951a4 4 0 0 1 4-4");
}

</style>
