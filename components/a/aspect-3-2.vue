<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9so1fywj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:aspect-3-2" /></template>
<style>
.p9so1fywj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.5 6.5H20q2.25 0 2.25 2.25v6.75q0 2.25-2.25 2.25h-3.5q-2.25 0-2.25-2.25V8.75q0-2.25 2.25-2.25M10.75 8H4q-2.25 0-2.25 2.25v3.5Q1.75 16 4 16h6.75Q13 16 13 13.75v-3.5Q13 8 10.75 8");
}

</style>
