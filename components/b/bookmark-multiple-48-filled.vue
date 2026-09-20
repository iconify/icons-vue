<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yyuqmm8le"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:bookmark-multiple-48-filled" /></template>
<style>
.yyuqmm8le {
  fill: currentColor;
  d: path("M14.668 6.5h14.081a7.75 7.75 0 0 1 7.75 7.75v24.081A5 5 0 0 0 39 34V14.25C39 8.59 34.41 4 28.75 4H19a5 5 0 0 0-4.331 2.5M14 9a5 5 0 0 0-5 5v28.75a1.25 1.25 0 0 0 1.943 1.04L21.5 36.752l10.557 7.038A1.25 1.25 0 0 0 34 42.75V14a5 5 0 0 0-5-5z");
}

</style>
