<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="akwanubbt"/><path class="vkz7z4rxt"/><path class="lomropbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bookshelf" /></template>
<style>
.akwanubbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.997 10.658L6.241 19.027l17.756 5.588l17.762-8.058z");
}

.lomropbtj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.241 31.754l17.756 5.588l17.762-8.058M24.261 15.186l4.478 1.487M6.242 19.027c-2.411.985-2.232 5.661 0 6.364m35.517 3.894c2.41-.985 2.23-5.662 0-6.364");
}

.vkz7z4rxt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.241 25.39l17.756 5.589l17.762-8.059");
}

</style>
