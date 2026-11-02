<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdj3p4boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-pyramid-fill-sharp" /></template>
<style>
.qdj3p4boc {
  fill: currentColor;
  d: path("M15.618 8H8.382l2.724-5.447a.998.998 0 0 1 1.788 0ZM5.382 14l2-4h9.236l2 4Zm14.236 2l2.276 4.553A1 1 0 0 1 21 22H3a1 1 0 0 1-.894-1.447L4.382 16Z");
}

</style>
