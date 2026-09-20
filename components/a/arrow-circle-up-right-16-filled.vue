<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xnn78ubkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-circle-up-right-16-filled" /></template>
<style>
.xnn78ubkp {
  fill: currentColor;
  d: path("M1 8a7 7 0 1 0 14 0A7 7 0 0 0 1 8m10-2.5V10a.5.5 0 0 1-1 0V6.707l-3.646 3.647a.5.5 0 0 1-.708-.708L9.293 6H6a.5.5 0 0 1 0-1h4.5a.5.5 0 0 1 .5.5");
}

</style>
