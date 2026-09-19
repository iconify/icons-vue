<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jfqe5f42i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ipray" /></template>
<style>
.jfqe5f42i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.234 39.645L24 42.5v-37l18.234 5.481zM24 11.781l18.233 5.139M24 16.806l18.233 4.225M5.766 39.645L24 42.5v-37L5.766 10.981zM24 11.781L5.766 16.92M24 16.806L5.766 21.031");
}

</style>
