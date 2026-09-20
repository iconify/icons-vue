<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnmusbcrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:install-desktop-sharp" /></template>
<style>
.nnmusbcrf {
  fill: currentColor;
  d: path("M8 21v-2H2V3h10v2H4v12h16v-3h2v5h-6v2zm9-7l-5-5l1.4-1.4l2.6 2.575V3h2v7.175L20.6 7.6L22 9z");
}

</style>
