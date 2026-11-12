<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt-rsfbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-return-corner-fill-sharp" /></template>
<style>
.lt-rsfbvs {
  fill: currentColor;
  d: path("M22 5v3H2V5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1M2 10h8v9a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Zm20 3v4a1 1 0 0 1-1 1h-5.586l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414L15.414 16H20v-3a1 1 0 0 1 2 0");
}

</style>
