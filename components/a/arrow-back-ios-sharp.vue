<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2u-dxewg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-back-ios-sharp" /></template>
<style>
.z2u-dxewg {
  fill: currentColor;
  d: path("M10 22L0 12L10 2l1.775 1.775L3.55 12l8.225 8.225z");
}

</style>
