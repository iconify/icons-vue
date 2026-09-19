<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l68dfto6w"/><path class="uph4zqc9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-google-18" /></template>
<style>
.l68dfto6w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.795 20.738l2.25-1.238m0 0v9m5.91-4.5h-1.463a2.257 2.257 0 0 0-2.25 2.25h0a2.257 2.257 0 0 0 2.25 2.25h1.463a2.257 2.257 0 0 0 2.25-2.25h0a2.257 2.257 0 0 0-2.25-2.25m0 0a2.257 2.257 0 0 0 2.25-2.25h0a2.257 2.257 0 0 0-2.25-2.25h-1.463a2.257 2.257 0 0 0-2.25 2.25h0a2.257 2.257 0 0 0 2.25 2.25");
}

.uph4zqc9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h24l9-9v-24a4 4 0 0 0-4-4m-5 0v37m-19-28v28m28-9h-37m37-19h-28");
}

</style>
