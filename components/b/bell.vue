<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="dzgvq7fhv"/><circle class="cwy35vdky"/><path class="xzzy5jo_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:bell" /></template>
<style>
.cwy35vdky {
  cx: 18px;
  cy: 3px;
  r: 3px;
  fill: var(--svg-color--ffac33, #ffac33);
}

.dzgvq7fhv {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M28 13c0 11 5 10 5 15c0 0 0 2-2 2H5c-2 0-2-2-2-2c0-5 5-4 5-15C8 7.478 12.477 3 18 3s10 4.478 10 10");
}

.xzzy5jo_i {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M18 36a4 4 0 0 0 4-4h-8a4 4 0 0 0 4 4");
}

</style>
