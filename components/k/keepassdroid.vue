<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="nmm0v__ki"/><path class="n2jo2drpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:keepassdroid" /></template>
<style>
.n2jo2drpr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 26a2.62 2.62 0 0 1 1.59 4.7l1.24 4.3h-5.66l1.24-4.3A2.62 2.62 0 0 1 24 26m-10.93-7.11v-4.58a10.93 10.93 0 0 1 21.86 0v4.58M7.48 30.45h12.21m8.62 0h12.21");
}

.nmm0v__ki {
  width: 33.04px;
  height: 23.12px;
  x: 7.48px;
  y: 18.89px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

</style>
