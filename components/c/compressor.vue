<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w54s7hbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:compressor" /></template>
<style>
.w54s7hbvn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.5v7.008m-4.485-2.803L24 12.506l4.485-2.802M9.704 19.515h28.591m-28.591 8.97h28.591M24 42.5v-7.008m-4.485 2.803L24 35.493l4.485 2.804");
}

</style>
