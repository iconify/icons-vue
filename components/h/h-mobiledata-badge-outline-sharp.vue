<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng6ilkb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:h-mobiledata-badge-outline-sharp" /></template>
<style>
.ng6ilkb5d {
  fill: currentColor;
  d: path("M8.692 16.5h1v-4h4.616v4h1v-9h-1v4H9.692v-4h-1zM4 20V4h16v16zm1-1h14V5H5zM5 5v14z");
}

</style>
