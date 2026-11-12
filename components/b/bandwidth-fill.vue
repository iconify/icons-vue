<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2pso1byg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bandwidth-fill" /></template>
<style>
.i2pso1byg {
  fill: currentColor;
  d: path("M3 4h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m6.707 5.707L8.414 11h7.172l-1.293-1.293a.999.999 0 1 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414L15.586 13H8.414l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414M3 18h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

</style>
