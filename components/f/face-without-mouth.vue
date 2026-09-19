<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><g class="fbp0m0b1e"><circle class="djvj59_xy"/><circle class="pchx_i0bq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:face-without-mouth" /></template>
<style>
.djvj59_xy {
  cx: 20.5px;
  cy: 28.5px;
  r: 5px;
}

.fbp0m0b1e {
  fill: var(--svg-color--664e27, #664e27);
}

.pchx_i0bq {
  cx: 43.5px;
  cy: 28.5px;
  r: 5px;
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

</style>
