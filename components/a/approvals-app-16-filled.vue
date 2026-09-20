<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qq8gqabcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:approvals-app-16-filled" /></template>
<style>
.qq8gqabcu {
  fill: currentColor;
  d: path("M8.314.256a.75.75 0 1 0-1.128.988l.687.786A6.5 6.5 0 1 0 15 8.5v-.25a.75.75 0 1 0-1.5 0v.25a5 5 0 1 1-5.695-4.952l-.62.708a.75.75 0 1 0 1.13.988l1.75-2a.75.75 0 0 0 0-.988zm3.491 5.99a.75.75 0 0 1-.05 1.059l-2.75 2.5A.75.75 0 0 1 7.97 9.78L6.72 8.53a.75.75 0 0 1 1.06-1.06l.745.744l2.22-2.019a.75.75 0 0 1 1.06.05");
}

</style>
