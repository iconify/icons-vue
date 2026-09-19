<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q2ytdablw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:diary-personal-journal" /></template>
<style>
.q2ytdablw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 38.613l9.63-13.36l13.083 6.802L43.5 9.387l-6.562 4.389M43.5 9.387l-1.909 7.712");
}

</style>
