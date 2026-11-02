<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9hcurb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:checkbox-partial-fill-sharp" /></template>
<style>
.r9hcurb1d {
  fill: currentColor;
  d: path("M3 20V4a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1m12-9H9a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2");
}

</style>
