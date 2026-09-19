<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v438ydbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:are-na" /></template>
<style>
.v438ydbrm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.25 35.258V12.742M24 29.629L4.5 18.371m0 11.258L24 18.371m9.75 16.887V12.742m9.75 16.887L24 18.371m0 11.258l19.5-11.258");
}

</style>
