<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="djils8ioy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-autofit-width-dotted-20-regular" /></template>
<style>
.djils8ioy {
  fill: currentColor;
  d: path("m15.192 16.142l1.7-1.641l-1.7-1.641a.5.5 0 0 1 .694-.72l1.886 1.821a.75.75 0 0 1 0 1.08l-1.886 1.82a.5.5 0 1 1-.694-.72M17 5a2 2 0 0 0-2-2H5a2 2 0 0 0-2 2v4.5a.5.5 0 0 0 1 0V5a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v4.5a.5.5 0 1 0 1 0zm-2 9.503a.5.5 0 0 1-.5.5H13a.5.5 0 1 1 0-1h1.5a.5.5 0 0 1 .5.5m-8 .5a.5.5 0 1 0 0-1H5.5a.5.5 0 0 0 0 1zm4-.5a.5.5 0 0 1-.5.5h-1a.5.5 0 1 1 0-1h1a.5.5 0 0 1 .5.5m-6.19 1.639L3.11 14.5l1.7-1.641a.5.5 0 0 0-.695-.72L2.23 13.961a.75.75 0 0 0 0 1.08l1.886 1.82a.5.5 0 1 0 .694-.72");
}

</style>
