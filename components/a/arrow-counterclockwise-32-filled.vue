<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vgkwe7ble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-counterclockwise-32-filled" /></template>
<style>
.vgkwe7ble {
  fill: currentColor;
  d: path("M26.5 16c0-5.799-4.701-10.5-10.5-10.5c-2.594 0-4.968.94-6.801 2.5h2.051a1.25 1.25 0 1 1 0 2.5h-5C5.56 10.5 5 9.94 5 9.25v-5a1.25 1.25 0 1 1 2.5 0v1.914A12.95 12.95 0 0 1 16 3c7.18 0 13 5.82 13 13s-5.82 13-13 13S3 23.18 3 16q0-.419.026-.831a1.25 1.25 0 1 1 2.495.157A11 11 0 0 0 5.5 16c0 5.799 4.701 10.5 10.5 10.5S26.5 21.799 26.5 16");
}

</style>
