<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xfy4t2mps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:coolapk" /></template>
<style>
.xfy4t2mps {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.208 20.416c-4.112-3.263-7.945-6.067-12.057-6.067a9.65 9.65 0 0 0 0 19.302c5.809 0 15.723-11.615 18.649-18.734L43.5 33.65c-2.888-2.22-7.995-5.996-12.8-9.651");
}

</style>
