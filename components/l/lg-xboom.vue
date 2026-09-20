<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="u7x1mq1bw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lg-xboom" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.u7x1mq1bw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.393 27.262v-6.53l3.332 6.537l3.332-6.528v6.528M8.943 20.731l4.415 6.538m0-6.538l-4.415 6.538M17.554 24c.92 0 1.666.732 1.666 1.635s-.746 1.634-1.666 1.634h-2.749V20.73h2.749c.92 0 1.666.732 1.666 1.635S18.474 24 17.554 24m0 0h-2.745m8.067-3.269zc1.219 0 2.207.97 2.207 2.166v2.206c0 1.196-.988 2.166-2.207 2.166c-1.22 0-2.208-.97-2.208-2.166v-2.206c0-1.196.988-2.166 2.208-2.166m5.862 0zc1.219 0 2.207.97 2.207 2.166v2.206c0 1.196-.988 2.166-2.207 2.166c-1.22 0-2.208-.97-2.208-2.166v-2.206c0-1.196.988-2.166 2.208-2.166");
}

</style>
