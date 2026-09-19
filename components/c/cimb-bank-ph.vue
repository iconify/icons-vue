<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eqd1vpbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cimb-bank-ph" /></template>
<style>
.eqd1vpbfy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 24H12.798L4.5 7.404h30.702zm-30.702 0L4.5 40.596h30.702L43.5 24");
}

</style>
