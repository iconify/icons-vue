<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brmof2bgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:line-start-arrow-notch-sharp" /></template>
<style>
.brmof2bgs {
  fill: currentColor;
  d: path("M11.808 16.827L4.212 12l7.596-4.827L9.402 11.5H21.5v1H9.402z");
}

</style>
