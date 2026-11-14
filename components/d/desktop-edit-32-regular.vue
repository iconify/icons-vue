<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nriiksbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desktop-edit-32-regular" /></template>
<style>
.nriiksbna {
  fill: currentColor;
  d: path("M20.837 5H5.25C4.56 5 4 5.56 4 6.25v15.5c0 .69.56 1.25 1.25 1.25h21.5c.69 0 1.25-.56 1.25-1.25V10.173l2-1.984V21.75A3.25 3.25 0 0 1 26.75 25h-6.744v2.001h2.998a1 1 0 0 1 0 2H9.012a1 1 0 0 1 0-2h2.998v-2H5.25A3.25 3.25 0 0 1 2 21.75V6.25A3.25 3.25 0 0 1 5.25 3h17.57zM14.01 27.001h3.996v-2H14.01zM25.572 2.35a2.88 2.88 0 0 1 4.144.058a2.88 2.88 0 0 1-.072 4.016l-8.609 8.543c-.351.349-.79.598-1.27.722l-3.019.777a1 1 0 0 1-1.217-1.219l.79-3.051a2.66 2.66 0 0 1 .686-1.205z");
}

</style>
