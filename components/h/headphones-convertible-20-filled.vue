<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vnnsicqda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:headphones-convertible-20-filled" /></template>
<style>
.vnnsicqda {
  fill: currentColor;
  d: path("M3.347 5.559a.478.478 0 0 1 .738-.06a.53.53 0 0 1 .058.667A6.97 6.97 0 0 0 3 10.001V11h3.5a.5.5 0 0 1 .5.5v6a.5.5 0 0 1-.5.5H4a2 2 0 0 1-2-2v-5.999a7.96 7.96 0 0 1 1.347-4.442M10 2a8 8 0 0 1 8 8.001V16a2 2 0 0 1-2 2h-2.5a.5.5 0 0 1-.5-.5v-6a.5.5 0 0 1 .5-.5H17v-.999A7 7 0 0 0 6.165 4.144a.53.53 0 0 1-.666-.059a.478.478 0 0 1 .059-.738A7.96 7.96 0 0 1 10 2");
}

</style>
