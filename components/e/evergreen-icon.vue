<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><circle class="doa4-pbgn"/><path class="az3ocgbvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:evergreen-icon" /></template>
<style>
.az3ocgbvy {
  fill: var(--svg-color--fff, #fff);
  d: path("M135.97 176.049v31.88h-15.94v-31.88zM128 56.5l55.79 111.579H72.21z");
}

.doa4-pbgn {
  cx: 128px;
  cy: 128px;
  r: 128px;
  fill: var(--svg-color--38a065, #38a065);
}

.ft5dv1b6b {
  fill: none;
}

</style>
