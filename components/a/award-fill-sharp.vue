<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqg6b-k0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:award-fill-sharp" /></template>
<style>
.xqg6b-k0r {
  fill: currentColor;
  d: path("m15.14 15.258l1.809 5.426a.999.999 0 0 1-1.396 1.21L12 20.118l-3.553 1.776a.999.999 0 0 1-1.396-1.21l1.809-5.426A7.003 7.003 0 0 1 12 2a7.002 7.002 0 0 1 3.14 13.258");
}

</style>
