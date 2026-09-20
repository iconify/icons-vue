<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnsfdr_so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:escalator-sharp" /></template>
<style>
.bnsfdr_so {
  fill: currentColor;
  d: path("M5.5 18h4.8l5-9h3.2V6h-4.8l-5 9H5.5zM3 21V3h18v18z");
}

</style>
