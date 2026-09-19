<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="om_0qzbij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:batteryone" /></template>
<style>
.om_0qzbij {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.5 3.5L14.834 23.481l7.797 3.22l-4.79 17.799l15.323-20.087l-8.174-2.442z");
}

</style>
