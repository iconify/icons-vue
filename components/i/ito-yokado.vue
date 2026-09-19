<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="jmdwq20ph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ito-yokado" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jmdwq20ph {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.922 10.738c-3.448 12.87-13.061 15.307-19.531 15.307c5.414 3.105 12.47 4.104 18.213 2.565v3.57S33.864 36 24 36c-11.612 0-15.049-5.095-15.908-9.74c-.916-4.957 1.108-9.483-4.342-9.483c.566-.566 2.661-1.09 2.661-1.09c0-4.051 5.544-4.762 6.744.067c.68 2.736 2.126 5.119 4.029 7.065C20.043 12.15 31.41 6.665 35.202 5.649");
}

</style>
