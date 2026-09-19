<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtl23bc2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-propane" /></template>
<style>
.mtl23bc2p {
  fill: currentColor;
  d: path("M17 6h-1V5c0-1.1-.9-2-2-2h-4c-1.1 0-2 .9-2 2v1H7c-3.31 0-6 2.69-6 6s2.69 6 6 6v3h2v-3h6v3h2v-3c3.31 0 6-2.69 6-6s-2.69-6-6-6m-7-1h4v1h-4z");
}

</style>
