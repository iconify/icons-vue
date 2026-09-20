<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u8yht_bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-circle-right-48-filled" /></template>
<style>
.u8yht_bnx {
  fill: currentColor;
  d: path("M24 4c11.046 0 20 8.954 20 20s-8.954 20-20 20S4 35.046 4 24S12.954 4 24 4m-3.634 28.616a1.25 1.25 0 0 0 1.768 1.768l9.5-9.5a1.25 1.25 0 0 0 0-1.768l-9.5-9.5a1.25 1.25 0 0 0-1.768 1.768L28.982 24z");
}

</style>
