<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6rvq84gk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:backpack" /></template>
<style>
.m6rvq84gk {
  fill: currentColor;
  d: path("M6 22q-.825 0-1.412-.587T4 20V8q0-1.4.85-2.45T7 4.15V2h3v2h4V2h3v2.15q1.3.35 2.15 1.4T20 8v12q0 .825-.587 1.413T18 22zm8.5-6h2v-4h-9v2h7z");
}

</style>
