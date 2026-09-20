<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kgllnw2fj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:lockers" /></template>
<style>
.kgllnw2fj {
  fill: currentColor;
  d: path("M192 72a8 8 0 0 1-8 8h-24a8 8 0 0 1 0-16h24a8 8 0 0 1 8 8m-8 24h-24a8 8 0 0 0 0 16h24a8 8 0 0 0 0-16M72 80h24a8 8 0 0 0 0-16H72a8 8 0 0 0 0 16m24 16H72a8 8 0 0 0 0 16h24a8 8 0 0 0 0-16m128-48v176a8 8 0 0 1-16 0v-16h-72v16a8 8 0 0 1-16 0v-16H48v16a8 8 0 0 1-16 0V48a16 16 0 0 1 16-16h160a16 16 0 0 1 16 16M120 192V48H48v144Zm16 0h72V48h-72Z");
}

</style>
