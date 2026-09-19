<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ua_qyd02m"/><path class="apf1fzs2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:granny-3" /></template>
<style>
.apf1fzs2y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.934 26.978c.476-.398.99-.579 2.143-.576l.268.002c.95 0 1.722.77 1.722 1.722h0c0 .95-.771 1.721-1.722 1.721m-1.324 0h1.324");
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

.ua_qyd02m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.117 22.142v-7.433h1.778c1.006 0 1.82.817 1.82 1.825s-.814 1.824-1.82 1.824h-1.778m1.778 0l1.778 3.782m7.185.001v-7.432l3.598 7.432v-7.432m1.772 7.432v-7.432l3.599 7.432v-7.432m5.37 0l-1.799 4.716l-1.799-4.716m1.799 7.432v-2.716m-14.908.254h-2.406m-.597 2.462l1.8-7.432l1.799 7.432m-10.685-5.632a1.8 1.8 0 0 0-1.799-1.8h0a1.8 1.8 0 0 0-1.8 1.8v3.834a1.8 1.8 0 0 0 1.8 1.799h0a1.8 1.8 0 0 0 1.8-1.8v-.984h-1.8M21.934 32.71c.476.398.99.58 2.142.58h.269c.95 0 1.722-.77 1.722-1.721h0c0-.951-.771-1.722-1.722-1.722");
}

</style>
