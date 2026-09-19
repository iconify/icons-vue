<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ih9t5ij0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:antenna-bars" /></template>
<style>
.ih9t5ij0a {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2M20 48h-6v-8h6zm10 0h-6V32h6zm10 0h-6V24h6zm10 0h-6V16h6z");
}

</style>
