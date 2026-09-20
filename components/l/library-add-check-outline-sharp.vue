<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrjhhvxqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:library-add-check-outline-sharp" /></template>
<style>
.mrjhhvxqt {
  fill: currentColor;
  d: path("m12.2 13.32l4.958-4.959l-.708-.719l-4.25 4.25l-2.15-2.138l-.708.708zM6.5 17V3h14v14zm1-1h12V4h-12zm-4 4V6.616h1V19h12.385v1zm4-16v12z");
}

</style>
