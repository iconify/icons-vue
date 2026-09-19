<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j19p7rwpz"/><path class="hn59j5qpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:easy-math" /></template>
<style>
.hn59j5qpg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.334 15.27c.444-.38.922-.552 1.997-.549l.25.002c.885 0 1.603.734 1.603 1.641h0c0 .907-.718 1.641-1.604 1.641m-1.233 0h1.233m.262 7.887l4.653 7.626l2.003-18.537h15.614M4.5 16.982v-4.378c0-.884.711-1.596 1.595-1.596h5.324m0 25.984H6.095A1.59 1.59 0 0 1 4.5 35.396V31.02m39 0v4.376c0 .884-.711 1.596-1.595 1.596h-5.324m0-25.984h5.324c.884 0 1.595.712 1.595 1.596v4.378");
}

.j19p7rwpz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.971 21.293L25.88 33.035m9.091 0L25.88 21.293m-14.546-.559c.443.38.922.554 1.996.554h.25c.886 0 1.604-.735 1.604-1.641h0c0-.907-.718-1.642-1.604-1.642");
}

</style>
