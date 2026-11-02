<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smw13vbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:car-fill-sharp" /></template>
<style>
.smw13vbgd {
  fill: currentColor;
  d: path("M3 9h.382l2.724-5.447A1 1 0 0 1 7 3h10c.379 0 .725.214.894.553L20.618 9H21a1 1 0 0 1 0 2v7a1 1 0 0 1-1 1h-1v1a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1v-1H9v1a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-1H4a1 1 0 0 1-1-1v-7a1 1 0 0 1 0-2m4.618-4l-2 4h12.764l-2-4ZM8 13a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm8.01 0H16a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
