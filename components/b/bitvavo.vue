<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kyi4pnmew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bitvavo" /></template>
<style>
.kyi4pnmew {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 36.97L31.8 24h11.7l-7.8 12.97zm-7.8 0l15.6-25.94H20.1L4.5 36.97z");
}

</style>
