<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e8i5qdbel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-lightning-48-filled" /></template>
<style>
.e8i5qdbel {
  fill: currentColor;
  d: path("M18.291 24a1 1 0 0 1 .872 1.49L15.501 32h3c1.29 0 1.978 1.52 1.128 2.49L9.974 45.5c-1.01 1.151-2.885.17-2.515-1.315L9 38H3.005a1 1 0 0 1-.905-1.425l5.631-12A1 1 0 0 1 8.637 24zM24 15.25A3.75 3.75 0 0 0 27.75 19H40v22a3 3 0 0 1-3 3H13.947l7.184-8.192c1.892-2.158.518-5.483-2.224-5.785l1.997-3.552c1.125-2-.32-4.47-2.614-4.471H8.635q-.326.001-.635.068V7a3 3 0 0 1 3-3h13zm15.462 1.25H27.75c-.69 0-1.25-.56-1.25-1.25V4.464z");
}

</style>
