<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ygcy4ztxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:large-orange-diamond" /></template>
<style>
.ygcy4ztxv {
  fill: var(--svg-color--f27a52, #f27a52);
  d: path("M2.018 32L32 2.019l29.981 29.98L32 61.982z");
}

</style>
