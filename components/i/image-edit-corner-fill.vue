<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrtyznjyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-edit-corner-fill" /></template>
<style>
.nrtyznjyi {
  fill: currentColor;
  d: path("m12.061 12.647l-1.354-1.354a2.415 2.415 0 0 0-3.414 0L2 16.586V5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v6a1 1 0 0 1-1 1h-8c-.411 0-.789.264-.939.647m1.097-5.426a2 2 0 1 0 3.684 1.558a2 2 0 0 0-3.684-1.558m-1.451 7.9a1 1 0 0 0 .293.203V21a1 1 0 0 1-1 1H5a3 3 0 0 1-2.984-2.683a1 1 0 0 0 .277-.196l6.414-6.414a.414.414 0 0 1 .586 0ZM13 21v-3c0-.265.105-.52.293-.707l4-4a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-4 4A1 1 0 0 1 17 22h-3a1 1 0 0 1-1-1");
}

</style>
