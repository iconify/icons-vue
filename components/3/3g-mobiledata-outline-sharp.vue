<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kiq5gsbub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:3g-mobiledata-outline-sharp" /></template>
<style>
.kiq5gsbub {
  fill: currentColor;
  d: path("M3.5 16.5v-1h5v-3h-5v-1h5v-3h-5v-1h6v9zm17-5v5h-8v-9h8v1h-7v7h6v-3H17v-1z");
}

</style>
