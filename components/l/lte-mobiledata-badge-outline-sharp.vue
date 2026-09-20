<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psgdf891z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:lte-mobiledata-badge-outline-sharp" /></template>
<style>
.psgdf891z {
  fill: currentColor;
  d: path("M4 16h5v-2H6V8H4zm6 0h2v-6h2V8H8v2h2zm5 0h5v-2h-3v-1h2v-2h-2v-1h3V8h-5zM1 21V3h22v18zm2-2h18V5H3zm0 0V5z");
}

</style>
