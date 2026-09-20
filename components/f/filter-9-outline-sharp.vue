<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgzfyrnov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-9-outline-sharp" /></template>
<style>
.zgzfyrnov {
  fill: currentColor;
  d: path("M12 14.5h4v-9h-5v5h4v3h-3zm3-5h-3v-3h3zM6.5 17V3h14v14zm1-1h12V4h-12zm-4 4V6.616h1V19h12.385v1zm4-4V4z");
}

</style>
