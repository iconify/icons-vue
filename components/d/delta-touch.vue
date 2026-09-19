<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pivkfrblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:delta-touch" /></template>
<style>
.pivkfrblr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.595 43.5V12.441H10.6L8.482 4.5h31.036l-2.137 8.014h-8.418V35.03z");
}

</style>
