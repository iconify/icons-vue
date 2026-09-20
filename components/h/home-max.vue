<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7oppydnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:home-max" /></template>
<style>
.h7oppydnm {
  fill: currentColor;
  d: path("M8 18.77V18H5.5q-1.458 0-2.479-1.021T2 14.5v-5q0-1.458 1.021-2.479T5.5 6h13q1.458 0 2.479 1.021T22 9.5v5q0 1.458-1.021 2.479T18.5 18H16v.77z");
}

</style>
