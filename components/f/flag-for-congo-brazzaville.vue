<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="hqsefccuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-congo-brazzaville" /></template>
<style>
.hqsefccuh {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2M8.447 47.113L47.113 8.447a28.2 28.2 0 0 1 8.402 8.382L16.83 55.516a28.2 28.2 0 0 1-8.383-8.403");
}

</style>
