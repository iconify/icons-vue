<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw8pumbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:burn-rate" /></template>
<style>
.uw8pumbzp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.765 20.281Q8.789 22.25 12 22.25t5.235-1.969q2.015-1.959 2.015-5.031q0-9.065-5.314-12.86q-.106-.076-.231-.111t-.255-.027q-.149.01-.282.076q-.134.066-.232.178q-.099.112-.146.254q-.048.141-.038.29q.233 3.505-.978 5.461q-.538-1.922-2.358-3.135q-.097-.065-.21-.097q-.143-.041-.292-.024q-.148.017-.278.089q-.131.073-.223.19q-.093.117-.134.26q-.378 1.324-1.608 3.546q-1.921 3.473-1.921 5.91q0 3.072 2.015 5.031M8.75 16.25Q8.75 13 12 13t3.25 3.25T12 19.5t-3.25-3.25");
}

</style>
