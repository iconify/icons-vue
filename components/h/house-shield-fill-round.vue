<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvvz23pxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-shield-fill-round" /></template>
<style>
.kvvz23pxt {
  fill: currentColor;
  d: path("M3 17v-5.185a5 5 0 0 1 1.707-3.763l4-3.5a5 5 0 0 1 6.586 0l4 3.5A5 5 0 0 1 21 11.815V17a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22H8a5 5 0 0 1-5-5m7-6a2 2 0 0 0-2 2v1c0 1.087.283 2.142.969 3c.676.844 1.629 1.417 2.584 1.894a1 1 0 0 0 .894 0C14.546 17.845 15.999 16.581 16 14v-1a2 2 0 0 0-2-2Z");
}

</style>
