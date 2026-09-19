<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vl9-lgbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dr-lyd" /></template>
<style>
.vl9-lgbhz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 6.904h4.055v25.579H5.5zm6.589 16.503h4.055v9.077h-4.055zm6.589-7.53h4.055v14.595h-4.055zm6.589 0h4.055v25.218h-4.055zm6.589 4.281h4.055v14.595h-4.055zm6.589-10.521H42.5v25.115h-4.055z");
}

</style>
