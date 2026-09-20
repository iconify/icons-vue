<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-tyoq94s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:html-outline-sharp" /></template>
<style>
.q-tyoq94s {
  fill: currentColor;
  d: path("M.154 14.692V9.308h.885v2h2.615v-2h.885v5.384h-.885v-2.5H1.039v2.5zm7.75 0v-4.5H5.96v-.884h4.77v.884H8.789v4.5zm4.25 0V9.308h5.885v5.384h-.885v-4.5h-1.616v3.5h-.884v-3.5h-1.616v4.5zm8.077 0V9.308h.884v4.5h2.731v.884z");
}

</style>
