<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="o8yzxqb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:klar" /></template>
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

.o8yzxqb-j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.22 24.926c0-1.462 1.167-2.647 2.606-2.647m-2.606.001v7.013M20.622 18.707v9.263c0 .73.583 1.323 1.303 1.323h.391m8.059-2.646c0 1.462-1.167 2.647-2.606 2.647s-2.607-1.185-2.607-2.647v-1.72c0-1.462 1.167-2.647 2.607-2.647s2.606 1.185 2.606 2.647m0 4.366V22.28m-18.202-3.573v10.586m0-3.688l5.604-6.864m0 10.552L13.49 24");
}

</style>
