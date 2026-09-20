<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="maef_lb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:bed-16-regular" /></template>
<style>
.maef_lb6p {
  fill: currentColor;
  d: path("M3 4.5A2.5 2.5 0 0 1 5.5 2h5A2.5 2.5 0 0 1 13 4.5v1.55a2.5 2.5 0 0 1 2 2.45v5a.5.5 0 0 1-1 0V11H2v2.5a.5.5 0 0 1-1 0v-5a2.5 2.5 0 0 1 2-2.45zM2 10h12V8.5A1.5 1.5 0 0 0 12.5 7h-9A1.5 1.5 0 0 0 2 8.5zm10-5.5A1.5 1.5 0 0 0 10.5 3h-5A1.5 1.5 0 0 0 4 4.5V6h1v-.5a.5.5 0 0 1 .5-.5H7a.5.5 0 0 1 .5.5V6h1v-.5A.5.5 0 0 1 9 5h1.5a.5.5 0 0 1 .5.5V6h1z");
}

</style>
