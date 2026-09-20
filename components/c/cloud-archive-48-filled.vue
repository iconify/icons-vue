<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bodpxebls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cloud-archive-48-filled" /></template>
<style>
.bodpxebls {
  fill: currentColor;
  d: path("M24 7c-6.29 0-11.45 4.84-11.959 11H11.5a8.5 8.5 0 0 0 0 17H24v-3.17A3 3 0 0 1 22 29v-3a3 3 0 0 1 3-3h19.248a8.5 8.5 0 0 0-7.748-5h-.541C35.45 11.84 30.29 7 24 7m1 18a1 1 0 0 0-1 1v3a1 1 0 0 0 1 1h20a1 1 0 0 0 1-1v-3a1 1 0 0 0-1-1zm1 7h18v9a4 4 0 0 1-4 4H30a4 4 0 0 1-4-4zm12 3h-6a1 1 0 1 0 0 2h6a1 1 0 1 0 0-2");
}

</style>
