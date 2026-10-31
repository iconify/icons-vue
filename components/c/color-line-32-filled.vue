<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l7b1yc70d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:color-line-32-filled" /></template>
<style>
.l7b1yc70d {
  fill: currentColor;
  d: path("M25.5 19a4.5 4.5 0 0 1 4.5 4.5v2a4.5 4.5 0 0 1-4.5 4.5h-19A4.5 4.5 0 0 1 2 25.5v-2a4.5 4.5 0 0 1 3.886-4.458l-.322 1.395a2.5 2.5 0 0 0 2.999 2.999l5.94-1.37a4.5 4.5 0 0 0 2.17-1.204L18.537 19zm-3-17A4.5 4.5 0 0 1 27 6.5v.05a4.5 4.5 0 0 1-1.318 3.182l-10.07 10.07a3 3 0 0 1-1.446.802l-5.941 1.37a1 1 0 0 1-1.2-1.199l1.371-5.941a3 3 0 0 1 .802-1.446l10.07-10.07A4.5 4.5 0 0 1 22.45 2z");
}

</style>
