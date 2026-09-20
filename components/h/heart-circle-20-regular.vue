<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sn4mr0bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:heart-circle-20-regular" /></template>
<style>
.sn4mr0bxf {
  fill: currentColor;
  d: path("M9.6 7.614L9.99 8l.4-.393a2.12 2.12 0 0 1 3.035 2.959l-3.06 3.273a.5.5 0 0 1-.73 0L6.57 10.561A2.113 2.113 0 0 1 9.6 7.614M2 10a8 8 0 1 1 16 0a8 8 0 0 1-16 0m8-7a7 7 0 1 0 0 14a7 7 0 0 0 0-14");
}

</style>
