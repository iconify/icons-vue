<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="huh9p-nme"/><path class="i1ejd0v3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:find-my-ip" /></template>
<style>
.huh9p-nme {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.751 43a34.4 34.4 0 0 1 13.219-2.653a34.2 34.2 0 0 1 13.279 2.629m-13.255-5.809s10.84-11.687 10.84-21.328C34.833 9.853 29.98 5 23.993 5S13.155 9.853 13.155 15.839c0 9.641 10.84 21.328 10.84 21.328m-3.322-25.105v10.043");
}

.i1ejd0v3s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.319 22.105V12.062h3.287c1.86 0 3.366 1.51 3.366 3.373s-1.507 3.373-3.366 3.373H23.32");
}

</style>
