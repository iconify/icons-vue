<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy65cbcoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:airline-stops-outline" /></template>
<style>
.vy65cbcoj {
  fill: currentColor;
  d: path("M9.596 18v-1h1.885q-.106-3.68-2.508-6.34T3 8V7q3.206 0 5.656 2.008t3.344 5.1q.777-2.372 2.471-4.146T18.36 7h-4.072V6H20v5.712h-1V7.796q-2.71 1.425-4.577 3.804T12.481 17h1.865v1z");
}

</style>
