<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ah6q_f1og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:lock-laminated-bold" /></template>
<style>
.ah6q_f1og {
  fill: currentColor;
  d: path("M208 76h-28V56a52 52 0 0 0-104 0v20H48a20 20 0 0 0-20 20v112a20 20 0 0 0 20 20h160a20 20 0 0 0 20-20V96a20 20 0 0 0-20-20M52 144h152v16H52Zm48-88a28 28 0 0 1 56 0v20h-56Zm104 44v20H52v-20ZM52 204v-20h152v20Z");
}

</style>
