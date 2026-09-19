<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ou-cipbqs"/><path class="xjom-0c0f"/><path class="zi8k4lqmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:coros" /></template>
<style>
.ou-cipbqs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.096 12.644L26.364 5.5l-12.02 7.57l-.512 14.289");
}

.xjom-0c0f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.247 11.62l10.966 7.456v15.825L27.418 42.5");
}

.zi8k4lqmo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.94 31.713l-12.36 6.689l-12.334-7.315l-.342-15.227");
}

</style>
