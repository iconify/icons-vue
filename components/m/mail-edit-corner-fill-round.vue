<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujo14haju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-edit-corner-fill-round" /></template>
<style>
.ujo14haju {
  fill: currentColor;
  d: path("M7.536 9.121L3.677 5.263A4.98 4.98 0 0 1 7 4h10c1.228 0 2.406.445 3.323 1.263l-3.859 3.858a3 3 0 0 1-2.121.879H9.657a3 3 0 0 1-2.121-.879M16.414 12l5.117-5.117c.31.664.47 1.384.469 2.117v2a1 1 0 0 1-1 1ZM2 9c0-.733.158-1.453.469-2.117l3.652 3.653A5 5 0 0 0 9.657 12H11v7a1 1 0 0 1-1 1H7a5 5 0 0 1-5-5Zm11 12v-3c0-.265.105-.52.293-.707l4-4a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-4 4A1 1 0 0 1 17 22h-3a1 1 0 0 1-1-1");
}

</style>
