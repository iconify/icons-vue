<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hwoh15byl"/><path class="o-uvrdb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:anime-indo" /></template>
<style>
.hwoh15byl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 40.022L24 7.979M20.318 28.53l-6.634 11.492h13.269z");
}

.o-uvrdb5q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.136 40.022L20.318 14.356L5.5 40.022");
}

</style>
