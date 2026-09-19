<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lyg9z8bdd"/><path class="y3alljbfo"/><path class="uzy84e0nr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:image-converter" /></template>
<style>
.lyg9z8bdd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.585 7l4 4l-4 4m7.961-4H37.5a4 4 0 0 1 4 4v18a4 4 0 0 1-4 4H16.762");
}

.uzy84e0nr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.659 30.349h16.682l-4.906-5.305l-1.543 1.542l-4.429-4.71z");
}

.y3alljbfo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.454 37H10.5a4 4 0 0 1-4-4V15a4 4 0 0 1 4-4h20.738M20.415 41l-4-4l4-4m7.548-15.35a2.392 2.392 0 1 1 0 4.785a2.392 2.392 0 0 1 0-4.784");
}

</style>
