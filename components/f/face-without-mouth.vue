<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="o-ea71vus"/><circle class="h9t2-2bdh"/><circle class="d23tr7b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:face-without-mouth" /></template>
<style>
.d23tr7b2u {
  cx: 43.5px;
  cy: 28.467px;
  r: 5px;
  fill: currentColor;
}

.h9t2-2bdh {
  cx: 20.5px;
  cy: 28.467px;
  r: 5px;
  fill: currentColor;
}

.o-ea71vus {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m0 57.5C16.836 59.5 4.5 47.164 4.5 32S16.836 4.5 32 4.5S59.5 16.836 59.5 32S47.164 59.5 32 59.5");
}

</style>
