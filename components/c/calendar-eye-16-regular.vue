<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xaqh-bcgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-eye-16-regular" /></template>
<style>
.xaqh-bcgg {
  fill: currentColor;
  d: path("M11.5 8c2.761 0 4.5 2.3 4.5 3.5c0 1.182-1.739 3.5-4.5 3.5S7 12.7 7 11.5C7 10.318 8.736 8 11.5 8m0-6A2.5 2.5 0 0 1 14 4.5v3.066a5.7 5.7 0 0 0-1-.37V6H3v5.5A1.5 1.5 0 0 0 4.5 13h1.92c.185.348.423.687.696 1H4.5A2.5 2.5 0 0 1 2 11.5v-7A2.5 2.5 0 0 1 4.5 2zm.957 7.19a2.501 2.501 0 1 0-1.915 4.622a2.501 2.501 0 0 0 1.915-4.622M11.5 10a1.5 1.5 0 1 1 0 2.999a1.5 1.5 0 0 1 0-2.999m-7-7A1.5 1.5 0 0 0 3 4.5V5h10v-.5A1.5 1.5 0 0 0 11.5 3z");
}

</style>
