<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wd2612b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aard" /></template>
<style>
.wd2612b2s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 10.35h-31a4 4 0 0 0-4 4v19.3a4 4 0 0 0 4 4h31a4 4 0 0 0 4-4v-19.3a4 4 0 0 0-4-4M9.38 15.57h12.26M9.38 21.24h12.26M9.38 26.92h12.26m0 5.68H9.38m16.98-17.03h12.27m-12.27 5.67h12.27m-12.27 5.68h12.27m0 5.68H26.36");
}

</style>
