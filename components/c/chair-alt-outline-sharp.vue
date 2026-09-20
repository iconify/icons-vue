<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5u5vi06c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chair-alt-outline-sharp" /></template>
<style>
.e5u5vi06c {
  fill: currentColor;
  d: path("M6.385 19.808V12.23h2.5v-2.077h-2.5V4.577h11.23v5.577h-2.5v2.077h2.5v7.577h-1v-3h-9.23v3zm1-10.654h9.23V5.577h-9.23zm2.5 3.077h4.23v-2.077h-4.23zm-2.5 3.577h9.23V13.23h-9.23zm0-6.654V5.577zm0 6.654V13.23z");
}

</style>
