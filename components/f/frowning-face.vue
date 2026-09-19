<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="o-ea71vus"/><circle class="a6uxc0blr"/><circle class="djz8f828d"/><path class="j_24j8ahg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:frowning-face" /></template>
<style>
.a6uxc0blr {
  cx: 20.5px;
  cy: 24.592px;
  r: 5px;
  fill: currentColor;
}

.djz8f828d {
  cx: 43.5px;
  cy: 24.592px;
  r: 5px;
  fill: currentColor;
}

.j_24j8ahg {
  fill: currentColor;
  d: path("M32 36.572c-6.354 0-11.314 3.604-13.771 7.65c-.658 1.082.217 2.254 1.188 1.578c8.109-5.656 17.107-5.623 25.168 0c.971.676 1.846-.496 1.188-1.578c-2.459-4.046-7.419-7.65-13.773-7.65");
}

.o-ea71vus {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m0 57.5C16.836 59.5 4.5 47.164 4.5 32S16.836 4.5 32 4.5S59.5 16.836 59.5 32S47.164 59.5 32 59.5");
}

</style>
