<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="to_cogbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-paragraph-24-filled" /></template>
<style>
.to_cogbmq {
  fill: currentColor;
  d: path("M21 2a1 1 0 0 1 1 1v4a3 3 0 0 1-3 3h-4.586l2.293 2.293a1 1 0 0 1-1.414 1.414l-4-4a1 1 0 0 1 0-1.414l4-4a1 1 0 1 1 1.414 1.414L14.414 8H19a1 1 0 0 0 1-1V3a1 1 0 0 1 1-1M7.293 11.293a1 1 0 0 0 0 1.414L9.586 15H3a1 1 0 1 0 0 2h6.586l-2.293 2.293a1 1 0 1 0 1.414 1.414l4-4a1 1 0 0 0 .293-.704V16a1 1 0 0 0-.295-.71l-3.998-3.997a1 1 0 0 0-1.414 0");
}

</style>
