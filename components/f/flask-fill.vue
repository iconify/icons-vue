<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9l0dcb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flask-fill" /></template>
<style>
.r9l0dcb5k {
  fill: currentColor;
  d: path("M8 2h8a1 1 0 0 1 0 2h-1v4.764l4.894 9.789c.181.356.274.75.273 1.149C20.164 20.924 19.265 22 18 22H6c-1.265 0-2.164-1.076-2.167-2.298a2.5 2.5 0 0 1 .273-1.149L9 8.764V4H8a1 1 0 0 1 0-2m3 7a1 1 0 0 1-.106.447L8.618 14h6.764l-2.276-4.553A1 1 0 0 1 13 9V4h-2Z");
}

</style>
