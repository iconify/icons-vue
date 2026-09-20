<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="qsk176bzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:contact-card-generic-28-filled" /></template>
<style>
.qsk176bzg {
  fill: currentColor;
  d: path("M23.25 4A2.75 2.75 0 0 1 26 6.75v14.5A2.75 2.75 0 0 1 23.25 24H4.75A2.75 2.75 0 0 1 2 21.25V6.75A2.75 2.75 0 0 1 4.75 4zM9.5 10a4 4 0 1 0 0 8a4 4 0 0 0 0-8m0 1.5a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5m6.25 3.5a.75.75 0 0 0 0 1.5h5.5a.75.75 0 0 0 0-1.5zm0-4a.75.75 0 0 0 0 1.5h5.5a.75.75 0 0 0 0-1.5z");
}

</style>
