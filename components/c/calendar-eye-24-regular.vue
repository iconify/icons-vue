<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1gmrde-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-eye-24-regular" /></template>
<style>
.p1gmrde-s {
  fill: currentColor;
  d: path("M17.5 13c3.038 0 5.5 3 5.5 4.5S20.538 22 17.5 22S12 19 12 17.5s2.462-4.5 5.5-4.5m.25-10A3.25 3.25 0 0 1 21 6.25v6.86c-.457-.3-.96-.561-1.5-.755V8.5h-15v9.25c0 .966.784 1.75 1.75 1.75h5.414c.314.515.729 1.03 1.22 1.5H6.25A3.25 3.25 0 0 1 3 17.75V6.25A3.25 3.25 0 0 1 6.25 3zm-.25 11.5a3 3 0 1 0 0 6a3 3 0 0 0 0-6m0 1.5a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3M6.25 4.5A1.75 1.75 0 0 0 4.5 6.25V7h15v-.75a1.75 1.75 0 0 0-1.75-1.75z");
}

</style>
