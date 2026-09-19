<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z71dke8se"/><path class="jj71sjbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:blokada-alt" /></template>
<style>
.jj71sjbus {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5c5.809-3.936 17.2-16.44 17.2-28.27c0-5.41-1.2-10.11-1.45-10.11c-.59 0-1.75 2.57-6 2.57c-5.32 0-8.69-3.19-9.75-3.19s-4.43 3.19-9.75 3.19c-4.25 0-5.41-2.57-6-2.57c-.25 0-1.45 4.7-1.45 10.11C6.8 27.06 18.192 39.564 24 43.5");
}

.z71dke8se {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.992 17.947l23.16 20.08M7.36 8.49l29.89 19.914L6.81 15.895m33.52 5.261L20.943 5.986");
}

</style>
