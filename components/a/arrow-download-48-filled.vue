<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nkf5_nbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-download-48-filled" /></template>
<style>
.nkf5_nbvr {
  fill: currentColor;
  d: path("M25.5 6.5a1.5 1.5 0 0 0-3 0v25.379l-7.94-7.94a1.5 1.5 0 0 0-2.12 2.122l10.5 10.5a1.5 1.5 0 0 0 2.12 0l10.5-10.5a1.5 1.5 0 0 0-2.12-2.122l-7.94 7.94zM10.5 40a1.5 1.5 0 0 0 0 3h27a1.5 1.5 0 0 0 0-3z");
}

</style>
