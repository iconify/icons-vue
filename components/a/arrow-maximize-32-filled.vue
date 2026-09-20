<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r0lql4dgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-maximize-32-filled" /></template>
<style>
.r0lql4dgl {
  fill: currentColor;
  d: path("M27.25 3.5c.69 0 1.25.56 1.25 1.25v10a1.25 1.25 0 1 1-2.5 0V7.768L7.768 26h6.982a1.25 1.25 0 1 1 0 2.5h-10c-.69 0-1.25-.56-1.25-1.25v-10a1.25 1.25 0 1 1 2.5 0v6.982L24.232 6H17.25a1.25 1.25 0 1 1 0-2.5z");
}

</style>
