<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="w8a6zebso"/><circle class="ku3ksj_5f"/><circle class="drzakmbwi"/><path class="svnhg94by"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:equalizer" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.drzakmbwi {
  cx: 35.719px;
  cy: 24.646px;
  r: 2.781px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ku3ksj_5f {
  cx: 24px;
  cy: 18.613px;
  r: 2.781px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.svnhg94by {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 21.394v14.925m11.719-8.893v8.893M12.281 25.17v11.149m0-16.711v-1.591m0-1.577v-1.591m0-1.578v-1.59M24 15.833v-.984m0-1.578v-1.59m11.719 7.927v-1.591m0 3.848v-.702m0-4.723v-1.591m0-1.578v-1.59");
}

.w8a6zebso {
  cx: 12.281px;
  cy: 22.389px;
  r: 2.781px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
