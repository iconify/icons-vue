<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojqt3f-ai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-9-plus-outline-sharp" /></template>
<style>
.ojqt3f-ai {
  fill: currentColor;
  d: path("M9.616 13.5H13v-7H9v4h3v2H9.616zM12 9.5h-2v-2h2zM6.5 17V3h14v14zm1-1h12V4h-12zm-4 4V6.616h1V19h12.385v1zm4-4V4zm8.616-3.5h1v-2H19v-1h-1.884v-2h-1v2h-2v1h2z");
}

</style>
