<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="jqx2qibtc"/><path class="cfv5grb9j"/><ellipse class="rmcz3fxop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:light-rail" /></template>
<style>
.cfv5grb9j {
  fill: currentColor;
  d: path("M34.226 35.23v13.91H62V19.856H41.55c-7.324 0-7.324 1.464-7.324 15.374");
}

.jqx2qibtc {
  fill: currentColor;
  d: path("M25.346 14C14.488 14 2 37.428 2 50.605c0 1.869.876 4.215 2.234 5.855H2V62h60v-5.539H7.735C5.64 56.399 4 52.713 4 50.605c0-.476.021-.967.054-1.465h8.176s13.182 0 13.182-7.32V19.856H17.86C20.377 17.469 22.959 16 25.346 16H62v-2z");
}

.rmcz3fxop {
  cx: 6.395px;
  cy: 52.801px;
  fill: currentColor;
  rx: 0.732px;
  ry: 2.197px;
}

</style>
