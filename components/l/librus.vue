<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a444elp8k"/><path class="y48qwuo3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:librus" /></template>
<style>
.a444elp8k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 33.26v2.02c0 3.99-3.23 7.22-7.22 7.22H12.72c-3.99 0-7.22-3.23-7.22-7.22V12.72c0-3.99 3.23-7.22 7.22-7.22H24v20.49a7.27 7.27 0 0 0 7.27 7.27z");
}

.y48qwuo3c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 12.72v11.43h-9.14V5.5h1.92c3.99 0 7.22 3.23 7.22 7.22");
}

</style>
