<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sc8gp-u-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-close-fill-sharp" /></template>
<style>
.sc8gp-u-d {
  fill: currentColor;
  d: path("m17.414 22l-9.707-9.707a1 1 0 0 0-1.414 0L2 16.586V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1Zm-1-13l1.293-1.293a.999.999 0 1 0-1.414-1.414L15 7.586l-1.293-1.293a.999.999 0 1 0-1.414 1.414L13.586 9l-1.293 1.293a.999.999 0 1 0 1.414 1.414L15 10.414l1.293 1.293a.999.999 0 1 0 1.414-1.414ZM4 17.414l3-3L14.586 22H3a1 1 0 0 1-1-1v-1.586Z");
}

</style>
