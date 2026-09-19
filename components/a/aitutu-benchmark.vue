<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pagf1kemu"/><path class="iocuxe7en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aitutu-benchmark" /></template>
<style>
.iocuxe7en {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.477 35.771l2.754-6.865h15.645m-5.177 2.32l1.823 4.545m-2.753-6.865L24 17.019l-3.761 9.376");
}

.pagf1kemu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.089 12.122c-1.32-1.192-1.553-2.807-1.204-4.824c-2.629 2.111-5.467 4.813-5.429 9.321c-1.243.127-2.177-.399-2.655-2.07c-2.979 2.196-5.22 7.656-5.216 10.916c.013 9.96 7.686 18.035 17.343 18.035s17.487-8.075 17.487-18.035c0-6.228-3.06-11.718-7.714-14.958c-.469 1.077-.797 1.888-2.14 2.765c-.127-5.416-4.298-6.537-7.38-8.772c.496 3.098-.506 6.555-3.092 7.622m-4.358 16.784h-3.607");
}

</style>
