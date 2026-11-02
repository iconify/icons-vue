<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izkg53yvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-up-right-bulk-sharp" /></template>
<style>
.izkg53yvu {
  fill: currentColor;
  d: path("M17 6a.997.997 0 0 1 1 1v7a1 1 0 0 1-2 0V9.414l-8.293 8.293a.999.999 0 1 1-1.414-1.414L14.586 8H10a1 1 0 0 1 0-2Z");
}

</style>
