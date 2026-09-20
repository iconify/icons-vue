<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rikfcf0pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:add-row-above-outline-sharp" /></template>
<style>
.rikfcf0pw {
  fill: currentColor;
  d: path("M5 20h14v-6H5zm16 2H3V4h4v2H5v6h14V6h-2V4h4zm-9-8v-2zm-1-6V6H9V4h2V2h2v2h2v2h-2v2z");
}

</style>
