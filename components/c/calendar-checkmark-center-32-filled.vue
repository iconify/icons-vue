<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a_hqclbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-checkmark-center-32-filled" /></template>
<style>
.a_hqclbsl {
  fill: currentColor;
  d: path("M29 24.5a4.5 4.5 0 0 1-4.5 4.5h-17A4.5 4.5 0 0 1 3 24.5V11h26zm-6.793-9.207a1 1 0 0 0-1.414 0L14.5 21.586l-2.793-2.793l-.076-.068a1 1 0 0 0-1.338 1.482l3.5 3.5a1 1 0 0 0 1.414 0l7-7a1 1 0 0 0 0-1.414M24.5 3A4.5 4.5 0 0 1 29 7.5V9H3V7.5A4.5 4.5 0 0 1 7.5 3z");
}

</style>
