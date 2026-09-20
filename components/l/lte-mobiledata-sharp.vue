<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igzb9qbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lte-mobiledata-sharp" /></template>
<style>
.igzb9qbln {
  fill: currentColor;
  d: path("M5.154 15.5v-7h1v6h3v1zm6.577 0v-6h-2v-1h5v1h-2v6zm4.769 0v-7h4v1h-3v2h3v1h-3v2h3v1z");
}

</style>
