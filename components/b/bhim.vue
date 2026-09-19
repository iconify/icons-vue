<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y6j6bk2fw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bhim" /></template>
<style>
.y6j6bk2fw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.801 22.51a1.284 1.284 0 0 1-.294 1.592m.294-1.592L21.171 4.5L10.19 42.346l20.316-18.244m7.146-.451a1.284 1.284 0 0 1-.294 1.592m.294-1.592l-9.51-17.97l-2.219 7.424m11.435 12.138L17.194 43.5l2.884-9.93");
}

</style>
