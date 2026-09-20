<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xt_legbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-square-16-filled" /></template>
<style>
.xt_legbej {
  fill: currentColor;
  d: path("M9 5.5A1.5 1.5 0 0 0 10.5 7H14v5.25A1.75 1.75 0 0 1 12.25 14h-8.5A1.75 1.75 0 0 1 2 12.25v-8.5C2 2.784 2.784 2 3.75 2H9zm1-3.42c.27.083.517.23.72.433l2.767 2.767c.203.203.35.45.434.72H10.5a.5.5 0 0 1-.5-.5z");
}

</style>
