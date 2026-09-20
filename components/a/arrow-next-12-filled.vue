<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="bpkwwsq4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-next-12-filled" /></template>
<style>
.bpkwwsq4b {
  fill: currentColor;
  d: path("M2.47 3.28a.75.75 0 0 1 1.06-1.06l3.25 3.25a.75.75 0 0 1 0 1.06L3.53 9.78a.75.75 0 0 1-1.06-1.06L5.19 6zM9.75 10a.75.75 0 0 0 .75-.75v-6.5a.75.75 0 0 0-1.5 0v6.5c0 .414.336.75.75.75");
}

</style>
