<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cdgonnczg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calculator-20-filled" /></template>
<style>
.cdgonnczg {
  fill: currentColor;
  d: path("M13.5 2h-7A2.5 2.5 0 0 0 4 4.5v11A2.5 2.5 0 0 0 6.5 18h7a2.5 2.5 0 0 0 2.5-2.5v-11A2.5 2.5 0 0 0 13.5 2m-6 2h5A1.5 1.5 0 0 1 14 5.5v1A1.5 1.5 0 0 1 12.5 8h-5A1.5 1.5 0 0 1 6 6.5v-1A1.5 1.5 0 0 1 7.5 4m.5 7a1 1 0 1 1-2 0a1 1 0 0 1 2 0m0 3a1 1 0 1 1-2 0a1 1 0 0 1 2 0m5-2a1 1 0 1 1 0-2a1 1 0 0 1 0 2m1 2a1 1 0 1 1-2 0a1 1 0 0 1 2 0m-4-2a1 1 0 1 1 0-2a1 1 0 0 1 0 2m1 2a1 1 0 1 1-2 0a1 1 0 0 1 2 0");
}

</style>
