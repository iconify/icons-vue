<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dfttxdb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:librescore" /></template>
<style>
.dfttxdb_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.462 28.11c0 6.87-4.946 8.122-7.28 6.97c-3.12-1.541-2.54-7.597 7.28-6.97V11.67h19.13v19.604H43.5v5.058H27.374V21.154H13.462m13.564-4.822H13.462");
}

</style>
