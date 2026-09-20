<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzs2pl16h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-self-stretch-outline-sharp" /></template>
<style>
.mzs2pl16h {
  fill: currentColor;
  d: path("M2 4V2h20v2zm0 18v-2h20v2zm8.5-4.5V6h3v11.5z");
}

</style>
