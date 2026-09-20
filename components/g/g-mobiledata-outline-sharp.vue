<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu_wdxieb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:g-mobiledata-outline-sharp" /></template>
<style>
.gu_wdxieb {
  fill: currentColor;
  d: path("M7 17V7h9v2H9v6h5v-2h-2v-2h4v6z");
}

</style>
