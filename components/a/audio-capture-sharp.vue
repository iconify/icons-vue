<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wok3v9y6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:audio-capture-sharp" /></template>
<style>
.wok3v9y6m {
  fill: currentColor;
  d: path("M3 20.077v-8.02h1v5.587l1.65-1.663h2.12V17H6.076zM16.23 17v-1.02H20v-3.922h1V17zm-4.73-2.192V5.942h1v8.866zm-3.788-1.962V7.904h1v4.942zm7.557-1V8.885h1v2.961zM3 7.942V3h4.77v1H4v3.942zm17 0V4h-3.77V3H21v4.942z");
}

</style>
