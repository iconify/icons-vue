<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mt1rp5bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:heart-circle-16-filled" /></template>
<style>
.mt1rp5bfz {
  fill: currentColor;
  d: path("M2 8a6 6 0 1 1 12 0A6 6 0 0 1 2 8m6-1l-.422-.492a1.465 1.465 0 1 0-2.156 1.98l2.4 2.44c.097.1.258.1.356 0l2.4-2.44a1.465 1.465 0 1 0-2.157-1.98z");
}

</style>
