<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dtkjyh0dj"/><path class="muuaolarw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:full-battery-charge-alarm" /></template>
<style>
.dtkjyh0dj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.154 8.404h-3.218V4.5h-7.872v3.904h-3.218a2.57 2.57 0 0 0-2.57 2.57V40.93a2.57 2.57 0 0 0 2.57 2.57h14.308a2.57 2.57 0 0 0 2.57-2.57V10.973a2.57 2.57 0 0 0-2.57-2.569m2.566 7.826H26m-1.13 0H14.28");
}

.muuaolarw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.894 24.966H26V14.112l-7.883 14.824h3.894V39.79z");
}

</style>
