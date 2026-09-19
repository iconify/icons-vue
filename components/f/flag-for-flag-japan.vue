<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="q6_5e3e_j"/><path class="umnd90b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-flag-japan" /></template>
<style>
.q6_5e3e_j {
  cx: 32px;
  cy: 32px;
  r: 11.8px;
  fill: currentColor;
}

.umnd90b4d {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m0 58C16.561 60 4 47.439 4 32S16.561 4 32 4s28 12.561 28 28s-12.561 28-28 28");
}

</style>
