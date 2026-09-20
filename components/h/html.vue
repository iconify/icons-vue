<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m368wbc5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:html" /></template>
<style>
.m368wbc5z {
  fill: currentColor;
  d: path("M.154 14.692V9.308h.885v2h2.615v-2h.885v5.384h-.885v-2.5H1.039v2.5zm7.75 0v-4.5H5.96v-.884h4.77v.884H8.789v4.5zm4.25 0v-4.615q0-.327.221-.548t.548-.221h4.346q.327 0 .548.22q.222.222.222.549v4.615h-.885v-4.5h-1.615v3.5h-.885v-3.5h-1.615v4.5zm8.077 0V9.308h.884v4.5h2.731v.884z");
}

</style>
