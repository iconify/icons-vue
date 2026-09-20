<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqajplvwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-back-ios-new-outline-sharp" /></template>
<style>
.oqajplvwg {
  fill: currentColor;
  d: path("M16 21.308L6.692 12L16 2.692l1.064 1.064L8.819 12l8.244 8.244z");
}

</style>
