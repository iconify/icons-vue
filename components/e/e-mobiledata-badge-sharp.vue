<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftq1pmo9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:e-mobiledata-badge-sharp" /></template>
<style>
.ftq1pmo9p {
  fill: currentColor;
  d: path("M8 17h8v-2h-6v-2h5v-2h-5V9h6V7H8zm-5 4V3h18v18z");
}

</style>
