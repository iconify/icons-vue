<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dwelhg-ld"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:chaoxing-mobile-ham1-fake" /></template>
<style>
.dwelhg-ld {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.91 22.222c-4.51 5.102 4.544 13.5 12.56 17.213m-10.168-1.73c-8.569-6.853-11.007-14.846-4.31-18.741m-2.667-1.616c-6.84 2.72-9.9 8.353-2.366 18.764m-8.497-1.447c-4.63-10.526-.072-16.82 7.683-18.632m11.802-2.89l-.802 4.09l5.618 4.966l-6.458-2.16l-1.521 3.665l-3.19-5.424l-6.557-2.702l4.486-1.192l-2.532-5.335l5.963 4.687z");
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
