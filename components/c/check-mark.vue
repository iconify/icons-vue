<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="w9pq_su7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:check-mark" /></template>
<style>
.w9pq_su7e {
  fill: var(--svg-color--405866, #405866);
  d: path("M60.59 11.873a6.58 6.58 0 0 0-9.165 1.621l-25.02 35.732L10 38.02a6.01 6.01 0 0 0-6.787 9.922l21.99 15.02a5.96 5.96 0 0 0 4.682.889a6.58 6.58 0 0 0 4.257-2.708l28.07-40.1a6.59 6.59 0 0 0-1.623-9.173");
}

</style>
