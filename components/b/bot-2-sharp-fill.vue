<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="awsq1zbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-2-sharp-fill" /></template>
<style>
.awsq1zbxp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1C18.0751 1 23 5.9249 23 12C23 18.0751 18.0751 23 12 23C5.9249 23 1 18.0751 1 12C1 5.9249 5.9249 1 12 1ZM10.882 6.9042L11.593 11.5685L13.5701 11.2671L12.8591 6.6028ZM14.8363 6.3014L15.5473 10.9657L17.5244 10.6643L16.8134 6Z");
}

</style>
