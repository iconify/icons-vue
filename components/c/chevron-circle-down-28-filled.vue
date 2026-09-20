<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="nj2k1ob3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-circle-down-28-filled" /></template>
<style>
.nj2k1ob3f {
  fill: currentColor;
  d: path("M2 14C2 7.373 7.373 2 14 2s12 5.373 12 12s-5.373 12-12 12S2 20.627 2 14m7.03-2.78a.75.75 0 0 0-1.06 1.06l5.5 5.5a.75.75 0 0 0 1.06 0l5.5-5.5a.75.75 0 1 0-1.06-1.06L14 16.19z");
}

</style>
