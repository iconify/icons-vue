<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="ic-371bqb"><path class="z64x-nlre"/><ellipse class="mxt0mtbff"/><path class="gi-hzfeaf"/><ellipse class="xt-ltvbde"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:double-exclamation-mark" /></template>
<style>
.gi-hzfeaf {
  d: path("M51 42.4H41L37 2h18z");
}

.ic-371bqb {
  fill: var(--svg-color--ff5a79, #ff5a79);
}

.mxt0mtbff {
  cx: 18px;
  cy: 54.4px;
  rx: 7.7px;
  ry: 7.6px;
}

.xt-ltvbde {
  cx: 46px;
  cy: 54.4px;
  rx: 7.7px;
  ry: 7.6px;
}

.z64x-nlre {
  d: path("M23 42.4H13L9 2h18z");
}

</style>
