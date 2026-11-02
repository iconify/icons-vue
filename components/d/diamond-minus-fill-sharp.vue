<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cau3u1blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:diamond-minus-fill-sharp" /></template>
<style>
.cau3u1blb {
  fill: currentColor;
  d: path("m17.707 17.707l-5 5a1 1 0 0 1-1.414 0l-10-10a1 1 0 0 1 0-1.414l10-10a1 1 0 0 1 1.414 0l10 10a1 1 0 0 1 0 1.414ZM15 11H9a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2");
}

</style>
