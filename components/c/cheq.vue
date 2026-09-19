<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cb8rs0vrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cheq" /></template>
<style>
.cb8rs0vrr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.348 28.83c4.46-9.265-4.074-19.265-13.195-19.265H4.5c.936 3.632 2.764 6.524 6.081 6.524l13.266.065c5.354.027 9.442 7.188 6.839 12.675zm-26.696-9.66c-4.46 9.265 4.074 19.265 13.195 19.265H43.5c-.936-3.632-2.764-6.524-6.081-6.524l-13.266-.065c-5.354-.027-9.442-7.188-6.839-12.675z");
}

</style>
