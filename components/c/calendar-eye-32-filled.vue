<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u2b80tbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-eye-32-filled" /></template>
<style>
.u2b80tbyo {
  fill: currentColor;
  d: path("M23.5 17.5c4.142 0 7.5 4 7.5 6s-3.358 6-7.5 6s-7.5-4-7.5-6s3.358-6 7.5-6m5.5.464C27.532 16.854 25.632 16 23.5 16c-2.553 0-4.774 1.224-6.32 2.646a10 10 0 0 0-1.889 2.322c-.444.768-.791 1.66-.791 2.532s.347 1.764.791 2.532a10.1 10.1 0 0 0 1.89 2.322q.363.333.773.646H7.5A4.5 4.5 0 0 1 3 24.5V11h26zM23.5 19.5a4 4 0 1 0 0 8a4 4 0 0 0 0-8m0 1.5a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5m1-18A4.5 4.5 0 0 1 29 7.5V9H3V7.5A4.5 4.5 0 0 1 7.5 3z");
}

</style>
