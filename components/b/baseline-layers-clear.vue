<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8holj7zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-layers-clear" /></template>
<style>
.g8holj7zg {
  fill: currentColor;
  d: path("m19.81 14.99l1.19-.92l-1.43-1.43l-1.19.92zm-.45-4.72L21 9l-9-7l-2.91 2.27l7.87 7.88zM3.27 1L2 2.27l4.22 4.22L3 9l1.63 1.27L12 16l2.1-1.63l1.43 1.43L12 18.54l-7.37-5.73L3 14.07l9 7l4.95-3.85L20.73 21L22 19.73z");
}

</style>
