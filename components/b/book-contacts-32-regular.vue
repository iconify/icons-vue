<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bq_lco29p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-contacts-32-regular" /></template>
<style>
.bq_lco29p {
  fill: currentColor;
  d: path("M9 4a2 2 0 0 0-2 2v18h18V6a2 2 0 0 0-2-2zM7 26a2 2 0 0 0 2 2h17a1 1 0 1 1 0 2H9a4 4 0 0 1-4-4V6a4 4 0 0 1 4-4h14a4 4 0 0 1 4 4v18.25A1.75 1.75 0 0 1 25.25 26zm12-15.5a3 3 0 1 1-6 0a3 3 0 0 1 6 0m2.5 6.75c0 1.868-1.571 3.75-5.5 3.75s-5.5-1.875-5.5-3.75v-.205c0-1.13.916-2.045 2.046-2.045h6.909c1.13 0 2.045.915 2.045 2.045z");
}

</style>
