<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h3qvp0zpf"/><path class="uph4zqc9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-google-25" /></template>
<style>
.h3qvp0zpf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.4 22.5c0-1.667 1.334-3 2.89-3s3 1.333 3 3c0 .778-.334 1.556-.89 2.111c-1.222 1-5 3.889-5 3.889h5.89m1.347-.787c.675.562 1.238.787 2.7.787h.338c1.575 0 2.925-1.35 2.925-2.925s-1.35-2.925-2.925-2.925h-3.038V19.5H30.6");
}

.uph4zqc9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h24l9-9v-24a4 4 0 0 0-4-4m-5 0v37m-19-28v28m28-9h-37m37-19h-28");
}

</style>
