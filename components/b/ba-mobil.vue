<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qi8s151-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ba-mobil" /></template>
<style>
.qi8s151-h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.001 17.803l5.367 9.296H23.36c-1.392 0-2.638.3-3.632 2.021l-2.806 4.923h24.474L24 3.915L5.794 35.435C-.14 25.987 2.14 13.57 11.042 6.845s21.47-5.522 28.936 2.769s7.348 20.916-.27 29.067S19.5 47.8 10.725 40.91z");
}

</style>
