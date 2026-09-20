<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aee-rob1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add" /></template>
<style>
.aee-rob1o {
  fill: currentColor;
  d: path("M11.5 12.5H6v-1h5.5V6h1v5.5H18v1h-5.5V18h-1z");
}

</style>
