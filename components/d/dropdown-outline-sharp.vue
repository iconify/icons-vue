<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5w-jz4wj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dropdown-outline-sharp" /></template>
<style>
.k5w-jz4wj {
  fill: currentColor;
  d: path("M11 13h7V6h-7zm-8 8V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
