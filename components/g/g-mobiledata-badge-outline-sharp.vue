<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y__ab2b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:g-mobiledata-badge-outline-sharp" /></template>
<style>
.y__ab2b-j {
  fill: currentColor;
  d: path("M8.5 16.5h7v-5h-2.615v1H14.5v3h-5v-7h6v-1h-7zM4 20V4h16v16zm1-1h14V5H5zM5 5v14z");
}

</style>
