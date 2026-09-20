<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcc7yob8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:file-download-off-outline" /></template>
<style>
.wcc7yob8h {
  fill: currentColor;
  d: path("M19.775 22.625L17.15 20H6q-.825 0-1.412-.587T4 18v-3h2v3h9.15l-2.575-2.575L12 16l-5-5l.575-.575l-6.2-6.2L2.8 2.8l18.4 18.4zm-4.35-10.05L14 11.15l1.6-1.6L17 11zM13 10.15l-2-2V4h2zm7 7l-2-2V15h2z");
}

</style>
