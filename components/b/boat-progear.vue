<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y5_5qyywr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:boat-progear" /></template>
<style>
.y5_5qyywr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.964 43H13.162l-4.466-8.806h30.608zM24 5l-9.371 26.644l17.255-5.664z");
}

</style>
