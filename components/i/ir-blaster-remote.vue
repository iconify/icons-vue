<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mtg0ep2za"/><path class="unyj6ubvf"/><circle class="xgrbmql7p"/><path class="q21wodbvf"/><path class="vn722wbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ir-blaster-remote" /></template>
<style>
.mtg0ep2za {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.107 10.699C19.31 7.763 21.44 5.5 24 5.5s4.69 2.263 4.893 5.199");
}

.q21wodbvf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 16.601v4.125m-8.694 4.417l.031-4.417h17.419v4.417m-25.75 0h33.987c.775 0 1.399.623 1.399 1.398v14.56c0 .775-.624 1.399-1.399 1.399H7.007a1.395 1.395 0 0 1-1.399-1.398v-14.56c0-.776.624-1.4 1.399-1.4");
}

.unyj6ubvf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.897 10.784C21.984 9.52 22.9 8.548 24 8.548s2.017.973 2.104 2.236");
}

.vn722wbyu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.809 29.004a.974.974 0 0 0-.976.976v1.518h-1.518a.974.974 0 0 0-.976.976v2.54c0 .54.435.976.976.976h1.518v1.517c0 .541.435.976.976.976h2.54c.54 0 .976-.435.976-.976V35.99h1.517c.54 0 .976-.436.976-.976v-2.54a.974.974 0 0 0-.976-.976h-1.517V29.98a.974.974 0 0 0-.976-.976zm22.385 0c.54 0 .975.435.975.976v1.518h1.518c.54 0 .976.435.976.976v2.54c0 .54-.435.976-.976.976H36.17v1.517a.973.973 0 0 1-.975.976h-2.54a.974.974 0 0 1-.977-.976V35.99H30.16a.974.974 0 0 1-.976-.976v-2.54c0-.541.435-.976.976-.976h1.517V29.98c0-.54.436-.976.976-.976z");
}

.xgrbmql7p {
  cx: 24.001px;
  cy: 14.462px;
  r: 2.14px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
