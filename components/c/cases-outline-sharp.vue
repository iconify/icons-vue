<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nj48e452u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:cases-outline-sharp" /></template>
<style>
.nj48e452u {
  fill: currentColor;
  d: path("M1 22V9h2v11h17v2zm4-4V5h5V1h8v4h5v13zm7-13h4V3h-4zM7 16h14V7H7zm0-9v9z");
}

</style>
