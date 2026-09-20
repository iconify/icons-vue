<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oslmlnblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:library-books-outline-sharp" /></template>
<style>
.oslmlnblh {
  fill: currentColor;
  d: path("M10 13.5h3.48v-1H10zm0-3h6.962v-1H10zm0-3h6.962v-1H10zM6.5 17V3h14v14zm1-1h12V4h-12zm-4 4V6.616h1V19h12.385v1zm4-16v12z");
}

</style>
