<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lq1ub8bof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-justify-center" /></template>
<style>
.lq1ub8bof {
  fill: currentColor;
  d: path("M11.5 21V3h1v18zm3.23-4.5v-9h2v9zm-7.46 0v-9h2v9z");
}

</style>
