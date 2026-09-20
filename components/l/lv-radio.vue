<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cjyydjbka"/><path class="zjznz51mz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lv-radio" /></template>
<style>
.cjyydjbka {
  cx: 24px;
  cy: 24px;
  r: 10.126px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zjznz51mz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.098 24l-6.123-3.537v7.074zm11.091-7.851c1.219 2.348 1.912 5.016 1.912 7.851s-.693 5.503-1.912 7.851M36.29 30.35c.988-1.899 1.54-4.054 1.54-6.35s-.552-4.451-1.54-6.35m5.914-3.066C43.679 17.394 44.5 20.6 44.5 24s-.821 6.607-2.296 9.416M8.811 31.851C7.592 29.504 6.9 26.835 6.9 24s.692-5.503 1.911-7.851m2.899 1.501c-.988 1.899-1.54 4.054-1.54 6.35s.552 4.452 1.54 6.35m-5.914 3.066C4.321 30.606 3.5 27.4 3.5 24s.821-6.607 2.296-9.416");
}

</style>
