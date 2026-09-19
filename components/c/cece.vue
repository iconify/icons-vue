<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="cv6u8pyap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cece" /></template>
<style>
.cv6u8pyap {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.34 25.468v.036a2.92 2.92 0 0 1-2.92 2.92h0a2.92 2.92 0 0 1-2.92-2.92V22.53a2.92 2.92 0 0 1 2.92-2.92h0a2.92 2.92 0 0 1 2.92 2.92v.036m6.268 4.746a2.2 2.2 0 0 1-1.915 1.112h0a2.203 2.203 0 0 1-2.203-2.203v-1.433c0-1.217.986-2.203 2.203-2.203h0c1.217 0 2.203.986 2.203 2.203v.716H18.49m12.453-.036v.036a2.92 2.92 0 0 1-2.92 2.92h0a2.92 2.92 0 0 1-2.92-2.92V22.53a2.92 2.92 0 0 1 2.92-2.92h0a2.92 2.92 0 0 1 2.92 2.92v.036m6.268 4.746a2.2 2.2 0 0 1-1.914 1.112h0a2.203 2.203 0 0 1-2.204-2.203v-1.433c0-1.217.987-2.203 2.204-2.203h0c1.217 0 2.203.986 2.203 2.203v.716h-4.407m-15.35-4.483c3.056.15 5.019-1.71 4.957-3.335c-.053-1.385-1.451-2.002-2.59-1.063c-.317-2.03-3.816-.888-2.554 1.547c.783 1.51.187 2.851.187 2.851");
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
