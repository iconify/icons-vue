<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ld3j_2c3q"/><circle class="dqhnj0bkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:appfinder" /></template>
<style>
.dqhnj0bkc {
  cx: 23.99px;
  cy: 25.039px;
  r: 2.726px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ld3j_2c3q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.56 22.294l-3.037-7.385L24.1 4.477l3.207 10.442l-2.706 7.375m-3.327 2.264l-7.946.601L4.5 18.526l10.922.19l6.213 4.89m5.03.942l8.017.611l8.818-6.633l-10.922.19l-6.203 4.88m-1.042 3.968l1.844 7.616l9.038 6.343l-3.547-10.331l-6.514-4.37m-3.497.602l-1.894 7.746l-9.028 6.353l3.547-10.331l6.574-4.47");
}

</style>
