<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w9upqtb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:goguma" /></template>
<style>
.w9upqtb6y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.548v36.904l7.238-7.303H42.5v-29.6zm15.51 6.203v16.776m5.947-16.776v16.776M15.905 16.922h16.093m0 6.336H15.905");
}

</style>
