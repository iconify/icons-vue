<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekrqi-byw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:http-outline-sharp" /></template>
<style>
.ekrqi-byw {
  fill: currentColor;
  d: path("M1.73 14.692V9.308h.886v2H5.23v-2h.885v5.384H5.23v-2.5H2.616v2.5zm7.27 0v-4.5H7.308v-.884h4.269v.884H9.885v4.5zm5.116 0v-4.5h-1.693v-.884h4.27v.884H15v4.5zm3.769 0V9.308h4.384v3.384h-3.5v2zm.884-2.884h2.616v-1.616h-2.616z");
}

</style>
