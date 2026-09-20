<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emllub-_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:combine-columns-sharp" /></template>
<style>
.emllub-_y {
  fill: currentColor;
  d: path("M3 21V3h8v4.1q-1.75.35-2.875 1.725T7 12t1.125 3.175T11 16.9V21zm10 0v-4.1q1.75-.35 2.875-1.725T17 12t-1.125-3.175T13 7.1V3h8v18zm-2-6v-2H9v-2h2V9h2v2h2v2h-2v2z");
}

</style>
