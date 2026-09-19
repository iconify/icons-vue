<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="voes2i1tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dhruv-rathee-academy" /></template>
<style>
.voes2i1tk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 6.559L5.5 41.441h6.943l7.59-6.852h-5.364L24 17.036M24 6.56l18.5 34.882h-6.943l-7.59-6.852h5.364L24 17.036");
}

</style>
