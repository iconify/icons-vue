<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4ep6ibnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dashboard-customize-outline-sharp" /></template>
<style>
.f4ep6ibnn {
  fill: currentColor;
  d: path("M3.5 3.5h7v7h-7zm1 1v5zm9-1h7v7h-7zm1 1v5zm-11 9h7v7h-7zm1 1v5zm12-1h1v3h3v1h-3v3h-1v-3h-3v-1h3zm-2-9v5h5v-5zm-10 0v5h5v-5zm0 10v5h5v-5z");
}

</style>
