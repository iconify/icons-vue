<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hwy-kwbhl"/><rect class="tg8vugi2c"/><path class="he77ygbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dreamdroid" /></template>
<style>
.he77ygbtj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.745 14.775v8.62c0 1.383-.252 2.569-3.26 2.569H13.96c-4.935 0-4.612-6.694-.124-6.694H29.2M13.142 30.768h4.346m-.885 4.582v2.519h14.893v-2.52");
}

.hwy-kwbhl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.022 30.768h4.346m1.534 0h4.345m1.535 0h4.345");
}

.tg8vugi2c {
  width: 39px;
  height: 25.218px;
  x: 4.5px;
  y: 10.131px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.096px;
  ry: 1.096px;
}

</style>
