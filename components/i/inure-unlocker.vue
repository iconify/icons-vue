<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c4zul1cio"/><path class="hamuewb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:inure-unlocker" /></template>
<style>
.c4zul1cio {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.5 32.126l8.277-14.238m-7.933 25.206l10.978-18.885M24 43.5c10.819 0 14.91-7.14 14.91-14.901V24.86c0-5.606-2.426-6.973-8.823-6.973H17.913c-6.397 0-8.822 1.367-8.822 6.973v3.737C9.09 36.362 13.18 43.5 24 43.5");
}

.hamuewb0y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.95 17.942V12.55a8.05 8.05 0 0 1 15.585-2.84m.515 8.232v-3.123");
}

</style>
