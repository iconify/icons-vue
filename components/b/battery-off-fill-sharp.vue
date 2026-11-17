<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mci-ycbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-off-fill-sharp" /></template>
<style>
.mci-ycbfc {
  fill: currentColor;
  d: path("m2.707 1.293l20 20a.999.999 0 1 1-1.414 1.414L16.586 18H3a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1h1.586L1.293 2.707a.999.999 0 1 1 1.414-1.414M19 14.757L10.243 6H18a1 1 0 0 1 1 1ZM22 10v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0");
}

</style>
