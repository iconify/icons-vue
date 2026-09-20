<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k_be_z5ze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-eye-20-filled" /></template>
<style>
.k_be_z5ze {
  fill: currentColor;
  d: path("M14.5 11c2.761 0 4.5 2.3 4.5 3.5c0 1.182-1.739 3.5-4.5 3.5S10 15.7 10 14.5c0-1.182 1.736-3.5 4.5-3.5m2.5-.434a5.79 5.79 0 0 0-6.469 1.009a5.5 5.5 0 0 0-1.097 1.406C9.18 13.451 9 13.983 9 14.5c0 .822.45 1.739 1.116 2.5H5.5A2.5 2.5 0 0 1 3 14.5V7h14zm-1.543 1.624a2.501 2.501 0 1 0-1.914 4.622a2.501 2.501 0 0 0 1.914-4.622M14.5 13a1.5 1.5 0 1 1 0 2.999a1.5 1.5 0 0 1 0-2.999m0-10A2.5 2.5 0 0 1 17 5.5V6H3v-.5A2.5 2.5 0 0 1 5.5 3z");
}

</style>
