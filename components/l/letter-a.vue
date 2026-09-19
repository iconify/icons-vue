<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="cxs_4_h0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:letter-a" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.cxs_4_h0e {
  fill: var(--svg-color--fff, #fff);
  d: path("M28.6 17.5h6.9l10.3 29h-6.6l-1.9-6H26.6l-2 6h-6.3zm-.4 18h7.4L32 24.1z");
}

</style>
