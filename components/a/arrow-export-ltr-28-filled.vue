<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="vd6yibbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-export-ltr-28-filled" /></template>
<style>
.vd6yibbmz {
  fill: currentColor;
  d: path("M3 5a1 1 0 0 1 1 1v16a1 1 0 1 1-2 0V6a1 1 0 0 1 1-1m14.793 1.793a1 1 0 0 1 1.414 0l6.5 6.5a1 1 0 0 1 0 1.414l-6.5 6.5a1 1 0 1 1-1.414-1.414L22.586 15H7a1 1 0 1 1 0-2h15.586l-4.793-4.793a1 1 0 0 1 0-1.414");
}

</style>
