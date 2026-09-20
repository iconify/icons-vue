<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yf5n_wa-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-template-32-filled" /></template>
<style>
.yf5n_wa-z {
  fill: currentColor;
  d: path("M2 6.5A4.5 4.5 0 0 1 6.5 2h15A4.5 4.5 0 0 1 26 6.5v5h-9.5a5 5 0 0 0-2.182.5H8a1 1 0 1 0 0 2h4.169a5 5 0 0 0-.669 2.5V26h-5A4.5 4.5 0 0 1 2 21.5zM7 9a1 1 0 0 0 1 1h12a1 1 0 1 0 0-2H8a1 1 0 0 0-1 1m6 7.5a3.5 3.5 0 0 1 3.5-3.5h10a3.5 3.5 0 0 1 3.5 3.5V18H13zm0 10V20h17v6.5a3.5 3.5 0 0 1-3.5 3.5h-10a3.5 3.5 0 0 1-3.5-3.5");
}

</style>
