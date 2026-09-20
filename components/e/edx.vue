<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ehffcgbdi"/><path class="b7qu5bcme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:edx" /></template>
<style>
.b7qu5bcme {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.856 23.594c-.633.754-1.581 1.262-2.512 1.262c-1.38 0-2.2-1.12-1.83-2.5l.435-1.626c.37-1.382 1.79-2.501 3.171-2.501s2.201 1.12 1.83 2.5l-.217.813h-5.002m12.913-.812c.37-1.382-.45-2.501-1.831-2.501s-2.8 1.12-3.171 2.5l-.436 1.626c-.37 1.381.45 2.5 1.831 2.5s2.8-1.119 3.171-2.5m-.67 2.501l2.68-10.003");
}

.ehffcgbdi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.774 12.3H8.605L4.5 27.9h22.168zM43.5 20.1H28.721l-4.105 15.6h14.779zM32.48 24l3.156 8m2.144-8l-7.444 8");
}

</style>
