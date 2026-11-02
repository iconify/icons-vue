<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scgpn4zdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-1-fill-sharp" /></template>
<style>
.scgpn4zdy {
  fill: currentColor;
  d: path("M13 4v4.586l.293-.293a1 1 0 0 1 1.414 0l5 5A1 1 0 0 1 20 14v5h1a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2h1V4a1 1 0 0 1 1-1h7a1 1 0 0 1 1 1m-2 1H6v14h2v-5c0-.265.105-.52.293-.707L11 10.586Z");
}

</style>
