<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c1a_01b7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:code-off-16-regular" /></template>
<style>
.c1a_01b7u {
  fill: currentColor;
  d: path("M1.146 1.147a.5.5 0 0 1 .707 0l13 13a.5.5 0 0 1-.707.707L7.885 8.59l-1.827 4.112a.5.5 0 1 1-.913-.406l1.982-4.464l-5.98-5.98a.5.5 0 0 1 0-.706m2.48 4.271a.5.5 0 0 1 .748.664L2.669 8l1.705 1.918a.5.5 0 0 1-.748.664l-2-2.25a.5.5 0 0 1 0-.664zm8.042-.041a.5.5 0 0 1 .706.041l2 2.25a.5.5 0 0 1 0 .664l-1.846 2.075l-.708-.708L13.331 8l-1.705-1.918a.5.5 0 0 1 .042-.705m-2.524-2.08a.5.5 0 1 1 .913.406l-1.303 2.93l-.757-.757z");
}

</style>
