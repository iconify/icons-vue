<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vf7z1zb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:engine-fill" /></template>
<style>
.vf7z1zb1e {
  fill: currentColor;
  d: path("M13 3a1 1 0 0 1 0 2h-1v2h1c.379 0 .725.214.894.553L15.618 11H17a2 2 0 0 1 2-2h1a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2h-1a2 2 0 0 1-2-2h-2v2a2 2 0 0 1-2 2h-3a1 1 0 0 1-.894-.553L7.382 17H7a2 2 0 0 1-2-2v-1H4v1a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0v1h1v-1c0-.265.105-.52.293-.707l3-3A1 1 0 0 1 9 7h1V5H9a1 1 0 0 1 0-2Z");
}

</style>
