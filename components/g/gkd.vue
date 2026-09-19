<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v2njbvbnt"/><path class="v7uhvjkvh"/><path class="bgrzktovj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gkd" /></template>
<style>
.bgrzktovj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.73 42.5c0-9.532 8.18-17.26 18.27-17.26s18.27 7.728 18.27 17.26z");
}

.v2njbvbnt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.101 14.813l-2.511-2.425l6.645-6.723l2.651 2.39L26.518 5.5l6.94 6.978l-2.637 2.505");
}

.v7uhvjkvh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.89 8.057l6.932 6.931l-6.932 6.702l-6.793-6.886zm7.684 18.79c-.244 5.243-.353 10.532-.23 15.653m-16.8-14.78c1.41 5.28.858 10.236.872 14.78");
}

</style>
