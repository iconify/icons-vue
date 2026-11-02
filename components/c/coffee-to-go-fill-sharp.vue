<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrh8olbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coffee-to-go-fill-sharp" /></template>
<style>
.qrh8olbed {
  fill: currentColor;
  d: path("M6.106 2.553A1 1 0 0 1 7 2h10c.379 0 .725.214.894.553l2 4A1 1 0 0 1 19 8h-.08l-.923 11.083c-.064.762-.327 1.504-.865 2.061c-.562.583-1.331.856-2.132.856H9c-.801 0-1.57-.273-2.132-.856c-.538-.557-.801-1.299-.865-2.061L5.08 8H5a1 1 0 0 1-.894-1.447ZM7.337 11h9.326l.25-3H7.087Zm.66 7.917C8.05 19.56 8.306 20 9 20h6c.694 0 .95-.44 1.003-1.083l.16-1.917H7.837Z");
}

</style>
