<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ze0m8brhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:file-map-outline-sharp" /></template>
<style>
.ze0m8brhx {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h14V5H5zm7-2.25q1.92-1.624 2.86-3.02q.94-1.397.94-2.585q0-1.803-1.142-2.849T12 7.25T9.342 8.298T8.2 11.143q0 1.186.947 2.583T12 16.75m-.753-4.846q-.305-.308-.305-.753t.308-.75t.753-.305t.75.308t.305.752t-.308.75t-.753.305t-.75-.307M5 19V5z");
}

</style>
