<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtl6j8blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-pyramid-fill" /></template>
<style>
.jtl6j8blr {
  fill: currentColor;
  d: path("M15.618 8H8.382l1.724-3.447a2.116 2.116 0 0 1 3.788 0ZM5.382 14l2-4h9.236l2 4Zm14.236 2l1.276 2.553c.181.356.274.75.273 1.149C21.164 20.924 20.265 22 19 22H5c-1.265 0-2.164-1.076-2.167-2.298a2.5 2.5 0 0 1 .273-1.149L4.382 16Z");
}

</style>
