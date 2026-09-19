<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ll0g54h-q"/><circle class="z6kz0pbfd"/><path class="c-3-ql74i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:etherpad" /></template>
<style>
.c-3-ql74i {
  fill: none;
  stroke: currentColor;
  d: path("M14.5 5.5v37m19-37v37");
}

.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

.z6kz0pbfd {
  cx: 24px;
  cy: 24px;
  r: 13.9px;
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 7;
}

</style>
