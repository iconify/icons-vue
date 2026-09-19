<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhuchrbkn"/><path class="im-o75nsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-quickreply" /></template>
<style>
.im-o75nsy {
  fill: currentColor;
  d: path("M22.5 16h-2.2l1.7-4h-5v6h2v5z");
}

.qhuchrbkn {
  fill: currentColor;
  d: path("M22 4c0-1.1-.9-2-2-2H4c-1.1 0-1.99.9-1.99 2L2 22l4-4h9v-8h7z");
}

</style>
