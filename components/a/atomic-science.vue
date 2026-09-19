<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s04my8bho"/><ellipse class="ovs6jy7mh"/><ellipse transform="rotate(-30 24 28.247)" class="u610xob7c"/><ellipse transform="rotate(-60 24 28.247)" class="ovs6jy7mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:atomic-science" /></template>
<style>
.ovs6jy7mh {
  cx: 24px;
  cy: 28.247px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.822px;
  ry: 11.5px;
}

.s04my8bho {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 15.5h-9a2 2 0 0 1-2-2v-9h-16a4 4 0 0 0-4 4v31a4 4 0 0 0 4 4h23a4 4 0 0 0 4-4zm-11-11l11 11");
}

.u610xob7c {
  cx: 24px;
  cy: 28.247px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 11.5px;
  ry: 4.822px;
}

</style>
