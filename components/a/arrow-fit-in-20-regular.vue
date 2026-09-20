<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gnsc7-ltv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-fit-in-20-regular" /></template>
<style>
.gnsc7-ltv {
  fill: currentColor;
  d: path("M5.646 7.354a.5.5 0 1 1 .708-.708l2.5 2.5a.5.5 0 0 1 0 .708l-2.5 2.5a.5.5 0 0 1-.708-.708L7.293 10H2.5a.5.5 0 0 1 0-1h4.793zm8.708 0a.5.5 0 0 0-.708-.708l-2.5 2.5a.5.5 0 0 0 0 .708l2.5 2.5a.5.5 0 0 0 .708-.708L12.707 10H17.5a.5.5 0 0 0 0-1h-4.793z");
}

</style>
