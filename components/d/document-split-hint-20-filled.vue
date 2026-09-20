<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hxac_edtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-split-hint-20-filled" /></template>
<style>
.hxac_edtb {
  fill: currentColor;
  d: path("M10 2v4.5A1.5 1.5 0 0 0 11.5 8H16v1.5a.5.5 0 0 1-.5.5h-11a.5.5 0 0 1-.5-.5v-6A1.5 1.5 0 0 1 5.5 2zm1 .25V6.5a.5.5 0 0 0 .5.5h4.25zM5 12a.5.5 0 0 0-1 0v1a.5.5 0 0 0 1 0zm11 0a.5.5 0 0 0-1 0v1a.5.5 0 0 0 1 0zM5 15.5a.5.5 0 0 0-1 0v.5a2 2 0 0 0 2 2h.5a.5.5 0 0 0 0-1H6a1 1 0 0 1-1-1zm11 0a.5.5 0 0 0-1 0v.5a1 1 0 0 1-1 1h-.5a.5.5 0 0 0 0 1h.5a2 2 0 0 0 2-2zM9 17a.5.5 0 0 0 0 1h2a.5.5 0 0 0 0-1z");
}

</style>
