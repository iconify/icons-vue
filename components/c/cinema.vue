<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="tpay_zhmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:cinema" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.tpay_zhmp {
  fill: var(--svg-color--fff, #fff);
  d: path("M42 16c-3 0-5.6 1.7-7 4.1c-1.4-2.5-4-4.1-7-4.1c-4.4 0-8 3.6-8 8s3.6 8 8 8c3 0 5.6-1.7 7-4.1c1.4 2.5 4 4.1 7 4.1c4.4 0 8-3.6 8-8s-3.6-8-8-8M28 27c-1.7 0-3-1.3-3-3s1.3-3 3-3s3 1.3 3 3s-1.3 3-3 3m14 0c-1.7 0-3-1.3-3-3s1.3-3 3-3s3 1.3 3 3s-1.3 3-3 3m4 5H23c-1.1 0-2 .9-2 2v.5L16 32v16l5-2.5v.5c0 1.1.9 2 2 2h23c1.1 0 2-.9 2-2V34c0-1.1-.9-2-2-2");
}

</style>
