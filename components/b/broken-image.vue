<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9ysc6weg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:broken-image" /></template>
<style>
.q9ysc6weg {
  fill: currentColor;
  d: path("M21 5v6.59l-3-3.01l-4 4.01l-4-4l-4 4l-3-3.01V5c0-1.1.9-2 2-2h14c1.1 0 2 .9 2 2m-3 6.42l3 3.01V19c0 1.1-.9 2-2 2H5c-1.1 0-2-.9-2-2v-6.58l3 2.99l4-4l4 4z");
}

</style>
