<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dd7anpj2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-fill-sharp" /></template>
<style>
.dd7anpj2o {
  fill: currentColor;
  d: path("M22 8H2V5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1Zm0 2v9a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-9Zm-11 4H7a1 1 0 0 0 0 2h4a1 1 0 0 0 0-2");
}

</style>
