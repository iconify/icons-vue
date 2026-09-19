<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uk4nzubsu"/><path class="pvbtn6bep"/><path class="ru5i80b0l"/><path class="zkwwtgdij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:katwarn" /></template>
<style>
.pvbtn6bep {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.82 31.222a13.5 13.5 0 0 0-24.281 8.122");
}

.ru5i80b0l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 20.864A21.952 21.952 0 0 0 9.82 39.417");
}

.uk4nzubsu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.876 39.344a5.434 5.434 0 0 0-10.867 0Z");
}

.zkwwtgdij {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.45 10.606A30.87 30.87 0 0 0 4.5 26.363");
}

</style>
