<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k50lr4bln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:briefcase-off-20-filled" /></template>
<style>
.k50lr4bln {
  fill: currentColor;
  d: path("M2.146 2.146a.5.5 0 0 1 .708 0l15 15a.5.5 0 0 1-.707.707l-1.062-1.061A3 3 0 0 1 15 17H5a3 3 0 0 1-3-3v-3.356A4 4 0 0 0 5 12h4v.5a.5.5 0 0 0 .5.5h1a.5.5 0 0 0 .5-.5V12h.293l-1.968-1.968A.5.5 0 0 0 9 10.5v.5H5a3 3 0 0 1-.639-5.932L2.146 2.854a.5.5 0 0 1 0-.708M18 14c0 .54-.146 1.046-.395 1.483L14.12 12H15a4 4 0 0 0 3-1.356zM11.25 2c.966 0 1.75.784 1.75 1.75V5h2a3 3 0 1 1 0 6h-1.879L7 4.879V3.75C7 2.784 7.784 2 8.75 2zm-2.5 1a.75.75 0 0 0-.75.75V5h4V3.75a.75.75 0 0 0-.75-.75z");
}

</style>
