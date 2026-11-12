<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myrvlobdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-return-corner-fill" /></template>
<style>
.myrvlobdh {
  fill: currentColor;
  d: path("M22 7v1H2V7a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3M2 10h8v9a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3Zm20 3v2a3 3 0 0 1-3 3h-3.586l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414L15.414 16H19a1 1 0 0 0 1-1v-2a1 1 0 0 1 2 0");
}

</style>
