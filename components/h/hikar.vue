<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ntz-uxbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hikar" /></template>
<style>
.ntz-uxbhu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.657 10.5v-6h-6.5v6m0 13v20h6.5v-20M35 10.5H6v13h29l7-6.5z");
}

</style>
