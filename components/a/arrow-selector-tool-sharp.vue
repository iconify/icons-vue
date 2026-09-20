<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ur1q23b4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-selector-tool-sharp" /></template>
<style>
.ur1q23b4v {
  fill: currentColor;
  d: path("m13.775 22l-3.625-7.8L6 20V2l14 11h-7.1l3.6 7.725z");
}

</style>
