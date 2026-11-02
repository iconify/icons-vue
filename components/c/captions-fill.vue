<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0x2_fcjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:captions-fill" /></template>
<style>
.h0x2_fcjh {
  fill: currentColor;
  d: path("M2 7a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm5 2a1 1 0 0 0 0 2h4a1 1 0 0 0 0-2Zm8 0a1 1 0 0 0 0 2h2a1 1 0 0 0 0-2Zm-6 4H7a1 1 0 0 0 0 2h2a1 1 0 0 0 0-2m8 0h-4a1 1 0 0 0 0 2h4a1 1 0 0 0 0-2");
}

</style>
