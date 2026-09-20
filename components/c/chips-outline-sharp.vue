<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdmhjibzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chips-outline-sharp" /></template>
<style>
.bdmhjibzm {
  fill: currentColor;
  d: path("M7 13h10v-2H7zm-4 8V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
