<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jg3elubtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:file-export-outline-sharp" /></template>
<style>
.jg3elubtc {
  fill: currentColor;
  d: path("m5.454 21.664l-.688-.714l3.45-3.45H5.234v-1h4.669v4.67h-1v-2.957zM12.289 21v-1H18V8h-4V4H6v10.116H5V3h9.5L19 7.5V21z");
}

</style>
