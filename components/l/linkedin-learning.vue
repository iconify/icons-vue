<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="te4vrp61p"/><path class="y72pm3b8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:linkedin-learning" /></template>
<style>
.te4vrp61p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.5 9.5h-35c-1.1 0-2 .9-2 2v25c0 1.1.9 2 2 2h35c1.1 0 2-.9 2-2v-25c0-1.1-.9-2-2-2");
}

.y72pm3b8k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.686 22.932l-9.145-5.266a1.233 1.233 0 0 0-1.848 1.069v10.53a1.233 1.233 0 0 0 1.848 1.069l9.145-5.265a1.233 1.233 0 0 0 0-2.137M24 9.5v10.006m0 8.836V38.5M8.25 31.991h12M8.25 24h10.442M8.25 16.009h12m7.5 15.982h12M30.303 24h9.447m-12-7.991h12");
}

</style>
