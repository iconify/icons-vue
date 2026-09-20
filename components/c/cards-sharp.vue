<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k42envb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:cards-sharp" /></template>
<style>
.k42envb_a {
  fill: currentColor;
  d: path("M6 11.5V6h5.5v5.5zM6 18v-5.5h5.5V18zm6.5-6.5V6H18v5.5zm0 6.5v-5.5H18V18zM3 21V3h18v18zm2-2h14V5H5z");
}

</style>
