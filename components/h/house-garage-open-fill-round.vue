<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxv64obji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-garage-open-fill-round" /></template>
<style>
.sxv64obji {
  fill: currentColor;
  d: path("M17 21.901V15a3 3 0 0 0-3-3h-4a3 3 0 0 0-3 3v6.901A5.01 5.01 0 0 1 3 17v-5.185a5 5 0 0 1 1.707-3.763l4-3.5a5 5 0 0 1 6.586 0l4 3.5A5 5 0 0 1 21 11.815V17a5.01 5.01 0 0 1-4 4.901");
}

</style>
