<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6zpstb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:crop-5-4-sharp" /></template>
<style>
.r6zpstb_t {
  fill: currentColor;
  d: path("M3 20V4h18v16z");
}

</style>
