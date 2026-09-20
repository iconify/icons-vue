<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nlvwl65bd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:browse-activity-outline-sharp" /></template>
<style>
.nlvwl65bd {
  fill: currentColor;
  d: path("M2 9V3h20v6h-2V5H4v4zm0 9v-7h2v5h16v-5h2v7zm0-7V9h6.6l1.475 2.875L13.425 6h1.2l1.5 3H22v2h-7.125l-.925-1.875L10.575 15h-1.2l-2-4zM1 21v-2h22v2zm11-10.5");
}

</style>
