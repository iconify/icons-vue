<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="auhinedmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:branch-compare-16-filled" /></template>
<style>
.auhinedmr {
  fill: currentColor;
  d: path("M9.146 5.854a.5.5 0 1 0 .708-.708L8.707 4H10.5A1.5 1.5 0 0 1 12 5.5v4.55a2.5 2.5 0 1 0 1 0V5.5A2.5 2.5 0 0 0 10.5 3H8.707l1.147-1.146a.5.5 0 0 0-.708-.708l-2 2a.5.5 0 0 0 0 .708zM6 3.5a2.5 2.5 0 0 1-2 2.45v4.55A1.5 1.5 0 0 0 5.5 12h1.793l-1.147-1.146a.5.5 0 0 1 .708-.708l2 2a.5.5 0 0 1 0 .708l-2 2a.5.5 0 0 1-.708-.708L7.293 13H5.5A2.5 2.5 0 0 1 3 10.5V5.95A2.5 2.5 0 1 1 6 3.5");
}

</style>
