<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nja9bvb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gta-vc" /></template>
<style>
.nja9bvb7f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.135 13.192l5.08 20.488a.677.677 0 0 0 1.25.161L27.206 7m10.812 6.02c4.449.456 3.707-10.442-5.69-3.536c-9.13 6.71-14.101 22.655-2 22.655c7.52 0 11.398-6.685 11.398-6.685M4.418 39.11c10.001-2.736 35.693-4.652 37.665-4.318s1.45 2.456.41 3.546");
}

</style>
