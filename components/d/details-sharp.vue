<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ailo9ub1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:details-sharp" /></template>
<style>
.ailo9ub1p {
  fill: currentColor;
  d: path("M2 21L12 3l10 18zm3.4-2H11V8.925zm7.6 0h5.6L13 8.925z");
}

</style>
