<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhcx4ioui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:currency-litecoin-fill" /></template>
<style>
.vhcx4ioui {
  fill: currentColor;
  d: path("M10 5v6.382l2.553-1.276a1 1 0 1 1 .894 1.788L10 13.618V18h9a1 1 0 0 1 0 2H9a1 1 0 0 1-1-1v-4.382l-2.553 1.276a1 1 0 1 1-.894-1.788L8 12.382V5a1 1 0 0 1 2 0");
}

</style>
