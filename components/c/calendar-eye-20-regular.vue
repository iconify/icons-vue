<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t6-kbsbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-eye-20-regular" /></template>
<style>
.t6-kbsbtk {
  fill: currentColor;
  d: path("M14.5 11c2.761 0 4.5 2.3 4.5 3.5c0 1.182-1.739 3.5-4.5 3.5S10 15.7 10 14.5c0-1.182 1.736-3.5 4.5-3.5m0-8A2.5 2.5 0 0 1 17 5.5v5.066a6 6 0 0 0-1-.37V7H4v7.5A1.5 1.5 0 0 0 5.5 16h3.92c.185.348.423.687.696 1H5.5A2.5 2.5 0 0 1 3 14.5v-9A2.5 2.5 0 0 1 5.5 3zm.957 9.19a2.501 2.501 0 1 0-1.914 4.622a2.501 2.501 0 0 0 1.914-4.622M14.5 13a1.5 1.5 0 1 1 0 2.999a1.5 1.5 0 0 1 0-2.999m-9-9A1.5 1.5 0 0 0 4 5.5V6h12v-.5A1.5 1.5 0 0 0 14.5 4z");
}

</style>
