<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atr7d-maa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dropdown-sharp" /></template>
<style>
.atr7d-maa {
  fill: currentColor;
  d: path("M11 13h7V6h-7zm-8 8V3h18v18z");
}

</style>
