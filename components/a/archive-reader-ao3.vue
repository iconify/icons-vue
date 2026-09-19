<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fr5b7ybdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:archive-reader-ao3" /></template>
<style>
.fr5b7ybdf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.5v37m17.7-29.1H6.3M34 33.8H14m10-20.4c-4.4 8-11.6 16.3-17.3 21.1M24 13.4c4.4 8 11.6 16.3 17.3 21.1");
}

</style>
