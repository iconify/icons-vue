<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="bd2n_ac8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:channel-share-12-filled" /></template>
<style>
.bd2n_ac8p {
  fill: currentColor;
  d: path("M3 1a2 2 0 0 0-2 2v3a2 2 0 0 0 2 2h3.085a1.5 1.5 0 1 0 0-1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1h1a2 2 0 0 0-2-2zm6 10a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2H5.915a1.5 1.5 0 1 0 0 1H9a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1H4a2 2 0 0 0 2 2z");
}

</style>
