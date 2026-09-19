<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i7u6rk80i"/><path class="fmyh_4b_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:intesa" /></template>
<style>
.fmyh_4b_e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.867 31.39v-7.908a4.133 4.133 0 0 1 8.266 0v7.909M9.5 31.39v-7.908a4.133 4.133 0 0 1 8.267 0v7.909m12.466-.001v-7.908a4.133 4.133 0 0 1 8.267 0v7.909");
}

.i7u6rk80i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-29 11.11h29");
}

</style>
