<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apnriuq1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lte-plus-mobiledata-badge-sharp" /></template>
<style>
.apnriuq1b {
  fill: currentColor;
  d: path("M5.154 15.5h3.192v-1H6.154v-6h-1zm4.885 0h1v-6h1.692v-1H8.346v1h1.693zm3.807 0h3.385v-1h-2.385v-2h1.885v-1h-1.885v-2h2.385v-1h-3.385zM2 20V4h20v7.558h-1.442v-1.442h-.885v1.442h-1.442v.884h1.442v1.443h.885v-1.443H22V20z");
}

</style>
