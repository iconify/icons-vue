<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="w_3ndhb3s"/><path class="sf44wvpci"/><circle class="eccar6q2e"/><path class="wv7xf4b7m"/><path class="bs8vcunkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:bellhop-bell" /></template>
<style>
.bs8vcunkv {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M33 31a2 2 0 0 1-2 2H5a2 2 0 0 1 0-4h26a2 2 0 0 1 2 2");
}

.eccar6q2e {
  cx: 18px;
  cy: 10px;
  r: 3px;
  fill: var(--svg-color--ffac33, #ffac33);
}

.sf44wvpci {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M30 18c0 7 3 4 3 7c0 0 0 2-2 2H5c-2 0-2-2-2-2c0-3 3 0 3-7c0-5.523 6.477-8 12-8s12 2.477 12 8");
}

.w_3ndhb3s {
  fill: var(--svg-color--f4900c, #f4900c);
  d: path("M15 26h6v4h-6z");
}

.wv7xf4b7m {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M35 33a2 2 0 0 1-2 2H3a2 2 0 0 1 0-4h30a2 2 0 0 1 2 2");
}

</style>
