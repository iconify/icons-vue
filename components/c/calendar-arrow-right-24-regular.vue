<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eu6p8nb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-arrow-right-24-regular" /></template>
<style>
.eu6p8nb1i {
  fill: currentColor;
  d: path("M21 6a3 3 0 0 0-3-3H6a3 3 0 0 0-3 3v12a3 3 0 0 0 3 3h6.022a6.5 6.5 0 0 1-.709-1.5H6A1.5 1.5 0 0 1 4.5 18V8.5h15v2.813a6.5 6.5 0 0 1 1.5.709zM6 4.5h12A1.5 1.5 0 0 1 19.5 6v1h-15V6A1.5 1.5 0 0 1 6 4.5m17 13a5.5 5.5 0 1 0-11 0a5.5 5.5 0 0 0 11 0m-5.354-2.146a.5.5 0 0 1 .708-.708l2.5 2.5a.5.5 0 0 1 0 .708l-2.5 2.5a.5.5 0 0 1-.708-.708L19.293 18H14.5a.5.5 0 0 1 0-1h4.793z");
}

</style>
