<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_ex_nb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-eye-24-filled" /></template>
<style>
.f_ex_nb4r {
  fill: currentColor;
  d: path("M17.5 13c3.038 0 5.5 3 5.5 4.5S20.538 22 17.5 22S12 19 12 17.5s2.462-4.5 5.5-4.5m3.5.11c-.984-.647-2.18-1.11-3.5-1.11c-1.848 0-3.457.906-4.575 1.96a7.4 7.4 0 0 0-1.364 1.712c-.32.567-.561 1.21-.561 1.828c0 .617.24 1.261.562 1.828c.323.572.776 1.15 1.322 1.672H6.25A3.25 3.25 0 0 1 3 17.75V8.5h18zm-3.5 1.39a3 3 0 1 0 0 6a3 3 0 0 0 0-6m0 1.5a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m.25-13A3.25 3.25 0 0 1 21 6.25V7H3v-.75A3.25 3.25 0 0 1 6.25 3z");
}

</style>
