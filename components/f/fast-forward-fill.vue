<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdpq_obco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fast-forward-fill" /></template>
<style>
.bdpq_obco {
  fill: currentColor;
  d: path("M11 9.397V8.5a2.501 2.501 0 0 1 3.76-2.159l6 3.5a2.5 2.5 0 0 1 0 4.318l-6 3.5A2.5 2.5 0 0 1 11 15.5v-.897l-5.24 3.056A2.5 2.5 0 0 1 2 15.5v-7a2.501 2.501 0 0 1 3.76-2.159Z");
}

</style>
