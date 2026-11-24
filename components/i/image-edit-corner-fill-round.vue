<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izkf4wboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-edit-corner-fill-round" /></template>
<style>
.izkf4wboz {
  fill: currentColor;
  d: path("M14 12c-.691 0-1.354.232-1.89.669l-.416-.389a3.825 3.825 0 0 0-5.401.013L2 16.586V7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v4a1 1 0 0 1-1 1Zm1.779-2.158a2 2 0 1 0-1.558-3.684a2 2 0 0 0 1.558 3.684M13 21v-3c0-.265.105-.52.293-.707l4-4a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-4 4A1 1 0 0 1 17 22h-3a1 1 0 0 1-1-1m-2.683-7.27l.738.691A3 3 0 0 0 11 15v6a1 1 0 0 1-1 1H7a4.99 4.99 0 0 1-4.584-3.001l5.291-5.292c.52-.52 1.3-.677 1.982-.402c.255.104.433.243.628.425");
}

</style>
