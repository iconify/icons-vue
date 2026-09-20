<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjr4xib0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:contacts-sharp" /></template>
<style>
.tjr4xib0k {
  fill: currentColor;
  d: path("M4 23v-2h16v2zM4 3V1h16v2zm8 10q1.25 0 2.125-.875T15 10t-.875-2.125T12 7t-2.125.875T9 10t.875 2.125T12 13M2 20V4h20v16zm3.75-2h12.5q-1.125-1.4-2.725-2.2T12 15t-3.525.8T5.75 18");
}

</style>
