<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u82-tjbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:format-quote" /></template>
<style>
.u82-tjbvp {
  fill: currentColor;
  d: path("M6 17h3l2-4V7H5v6h3zm8 0h3l2-4V7h-6v6h3z");
}

</style>
