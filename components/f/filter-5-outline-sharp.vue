<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3xcwf9ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-5-outline-sharp" /></template>
<style>
.s3xcwf9ce {
  fill: currentColor;
  d: path("M11 14.5h5v-5h-4v-3h4v-1h-5v5h4v3h-4zM6.5 17V3h14v14zm1-1h12V4h-12zm-4 4V6.616h1V19h12.385v1zm4-4V4z");
}

</style>
