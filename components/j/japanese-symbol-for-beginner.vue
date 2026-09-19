<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="lm3xcm3_i"/><path class="ll_ogpufg"/><path class="h8s3lnnkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:japanese-symbol-for-beginner" /></template>
<style>
.h8s3lnnkv {
  fill: none;
  stroke: var(--svg-color--3e4347, #3e4347);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--3px, 3px);
  d: path("M32 20.8L12 2v41.2L32 62l20-18.8V2z");
}

.ll_ogpufg {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("M12 2v41.2L32 62V20.8z");
}

.lm3xcm3_i {
  fill: var(--svg-color--24bac5, #24bac5);
  d: path("M32 20.8V62l20-18.8V2z");
}

</style>
