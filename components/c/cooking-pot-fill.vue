<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwnr1n-rc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cooking-pot-fill" /></template>
<style>
.hwnr1n-rc {
  fill: currentColor;
  d: path("M14 5h-1v1.066A7.5 7.5 0 0 1 18.634 10H5.366A7.51 7.51 0 0 1 11 6.066V5h-1a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2m6 8h1a1 1 0 0 1 0 2h-1v3a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3v-3H3a1 1 0 0 1 0-2h1v-1h16Z");
}

</style>
