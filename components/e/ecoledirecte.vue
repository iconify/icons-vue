<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="do7j2u8-i"/><circle class="oxvdtlurq"/><path class="xwmw_8bff"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ecoledirecte" /></template>
<style>
.do7j2u8-i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.573 27.827a1.64 1.64 0 0 1-1.428.831h0A1.645 1.645 0 0 1 9.5 27.011v-1.07c0-.91.736-1.646 1.644-1.646h0c.907 0 1.644.737 1.644 1.646v.535H9.5m1.069-3.581l1.151-.412m9.25 6.175a1.645 1.645 0 0 1-1.644-1.647v-1.07c0-.91.736-1.646 1.644-1.646h0c.908 0 1.644.737 1.644 1.646v1.07c0 .91-.736 1.647-1.644 1.647m3.377-6.586v5.763c0 .455.368.823.822.823h.246m-7.822-.829c-.283.495-.817.83-1.428.83h0a1.645 1.645 0 0 1-1.644-1.647v-1.07c0-.91.736-1.647 1.644-1.647h0c.61 0 1.143.332 1.426.826m12.629 2.706a1.64 1.64 0 0 1-1.428.831h0a1.645 1.645 0 0 1-1.644-1.647v-1.07c0-.91.736-1.646 1.644-1.646h0c.908 0 1.644.737 1.644 1.646v.535h-3.288M12.788 38.29v-6.585m0 3.869c0-.91-.736-1.647-1.644-1.647h0c-.908 0-1.644.738-1.644 1.647v1.07c0 .91.736 1.647 1.644 1.647h0c.908 0 1.644-.737 1.644-1.647m4.452-2.716v4.363m0-2.717c0-.91.735-1.647 1.643-1.647h0");
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

.oxvdtlurq {
  cx: 15.014px;
  cy: 31.91px;
  r: 0.749px;
  fill: currentColor;
}

.xwmw_8bff {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.014 33.928v4.363m16.411-4.364h1.727m-.864-1.358v5.722m-8.272-.831c-.283.496-.816.83-1.428.83h0a1.645 1.645 0 0 1-1.644-1.646v-1.07c0-.91.736-1.647 1.644-1.647h0c.908 0 1.644.738 1.644 1.647v.535h-3.288m17.341 1.351c-.283.496-.817.83-1.428.83h0a1.645 1.645 0 0 1-1.645-1.646v-1.07c0-.91.736-1.647 1.644-1.647h0c.908 0 1.644.738 1.644 1.647v.535h-3.287m-5.849 1.353a1.64 1.64 0 0 1-1.427.829h0a1.645 1.645 0 0 1-1.644-1.647v-1.07c0-.91.736-1.647 1.644-1.647h0c.61 0 1.142.333 1.426.827");
}

</style>
