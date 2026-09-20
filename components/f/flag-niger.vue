<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="vbxe0xtoi"/><path class="m1kuipbpo"/><circle class="mfz-6wltb"/><path class="qqv_xg1zu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-niger" /></template>
<style>
.m1kuipbpo {
  fill: var(--svg-color--e05206, #e05206);
  d: path("M32 5H4a4 4 0 0 0-4 4v4h36V9a4 4 0 0 0-4-4");
}

.mfz-6wltb {
  cx: 18px;
  cy: 18px;
  r: 4px;
  fill: var(--svg-color--e05206, #e05206);
}

.qqv_xg1zu {
  fill: var(--svg-color--0db02b, #0db02b);
  d: path("M32 31H4a4 4 0 0 1-4-4v-4h36v4a4 4 0 0 1-4 4");
}

.vbxe0xtoi {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 13h36v10H0z");
}

</style>
