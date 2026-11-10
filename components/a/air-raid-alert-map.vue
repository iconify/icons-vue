<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mt_0uacow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:air-raid-alert-map" /></template>
<style>
.mt_0uacow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.251 33.589h21.498v7.972H13.251zm2.189 0v-6.093a8.56 8.56 0 1 1 17.12 0v6.093M24 16.535V6.439m8.944 13.232l4.116-4.116m-2.058 10.707H42.5m-27.444-6.591l-4.116-4.116m2.058 10.707H5.5");
}

</style>
