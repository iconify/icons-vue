<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pa4in_bid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hipaint" /></template>
<style>
.pa4in_bid {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.557 35.104H16.168V42.5H7.065V25.422h14.802l11.389-5.12l-11.389-4.561H6.487V5.5h19.932c19.932.569 19.932 28.466 1.138 29.604");
}

</style>
