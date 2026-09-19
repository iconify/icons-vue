<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="fpvn9lotp"/><path class="uxfuh-l2a"/><circle class="br47gjbyd"/><circle class="kqp9a46rs"/><circle class="n9ope8bhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:alert-bridge" /></template>
<style>
.br47gjbyd {
  cx: 20.515px;
  cy: 22.191px;
  r: 0.75px;
  fill: currentColor;
}

.fpvn9lotp {
  width: 23.766px;
  height: 26.803px;
  x: 12.117px;
  y: 10.598px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.726px;
}

.kqp9a46rs {
  cx: 24px;
  cy: 22.191px;
  r: 0.75px;
  fill: currentColor;
}

.n9ope8bhy {
  cx: 27.485px;
  cy: 22.191px;
  r: 0.75px;
  fill: currentColor;
}

.uxfuh-l2a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.398 10.599l-.758-5.357a.86.86 0 0 0-.855-.742h-13.57a.86.86 0 0 0-.854.742l-.759 5.357m0 26.803l.758 5.356a.86.86 0 0 0 .855.742h13.57a.86.86 0 0 0 .854-.742l.759-5.357m-1.726-21.799H17.328a1.726 1.726 0 0 0-1.726 1.726v14.785l3.388-3.388h11.682a1.726 1.726 0 0 0 1.726-1.727v-9.67a1.726 1.726 0 0 0-1.726-1.726");
}

</style>
