<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d92lyn2ge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-selector-tool-outline" /></template>
<style>
.d92lyn2ge {
  fill: currentColor;
  d: path("M8 13.75L9.975 11h4.25L8 6.1zM13.775 22l-3.625-7.8L6 20V2l14 11h-7.1l3.6 7.725zm-3.8-11");
}

</style>
