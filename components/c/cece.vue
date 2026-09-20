<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="r-446gbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cece" /></template>
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

.r-446gbjg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.34 25.468v.036a2.92 2.92 0 1 1-5.839 0V22.53a2.92 2.92 0 1 1 5.839 0v.036m6.268 4.746a2.203 2.203 0 0 1-4.118-1.091v-1.433a2.203 2.203 0 0 1 4.407 0v.716H18.49m12.453-.036v.036a2.92 2.92 0 1 1-5.839 0V22.53a2.92 2.92 0 1 1 5.839 0v.036m6.268 4.746a2.203 2.203 0 0 1-4.118-1.091v-1.433a2.203 2.203 0 0 1 4.407 0v.716h-4.407m-15.35-4.483c3.056.15 5.019-1.71 4.957-3.335c-.053-1.385-1.451-2.002-2.59-1.063c-.317-2.03-3.816-.888-2.554 1.547c.783 1.51.187 2.851.187 2.851");
}

</style>
