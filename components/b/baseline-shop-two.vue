<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="don8ziruo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-shop-two" /></template>
<style>
.don8ziruo {
  fill: currentColor;
  d: path("M3 9H1v11c0 1.11.89 2 2 2h14c1.11 0 2-.89 2-2H3zm15-4V3c0-1.11-.89-2-2-2h-4c-1.11 0-2 .89-2 2v2H5v11c0 1.11.89 2 2 2h14c1.11 0 2-.89 2-2V5zm-6-2h4v2h-4zm0 12V8l5.5 3z");
}

</style>
