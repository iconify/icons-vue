<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs9046bxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:laptop-chromebook-sharp" /></template>
<style>
.vs9046bxp {
  fill: currentColor;
  d: path("M0 20v-2h2V3h20v15h2v2zm10-2h4v-1h-4z");
}

</style>
