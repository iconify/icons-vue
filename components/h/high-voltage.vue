<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="h748ltbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:high-voltage" /></template>
<style>
.h748ltbds {
  fill: var(--svg-color--fbb11c, #fbb11c);
  d: path("M32 29L42 1L12 35h20L22 63l30-34");
}

</style>
