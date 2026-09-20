<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="nm6ym_bmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-step-in-right-28-regular" /></template>
<style>
.nm6ym_bmz {
  fill: currentColor;
  d: path("M9.707 19.768a.75.75 0 0 1 .025-1.06l4.146-3.958H2.75a.75.75 0 0 1 0-1.5h11.128L9.732 9.293a.75.75 0 1 1 1.036-1.086l5.5 5.25a.75.75 0 0 1 0 1.085l-5.5 5.25a.75.75 0 0 1-1.06-.024M22 10a4 4 0 1 1 0 8a4 4 0 0 1 0-8m0 1.5a2.5 2.5 0 1 0 0 5a2.5 2.5 0 0 0 0-5");
}

</style>
