<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ng2uivbgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:heart-48-filled" /></template>
<style>
.ng2uivbgb {
  fill: currentColor;
  d: path("M21.263 10.179a10.77 10.77 0 0 0-12.575-.296c-5.65 3.865-6.308 11.953-1.357 16.68l15.806 15.092a1.25 1.25 0 0 0 1.726 0l15.803-15.09c4.952-4.729 4.293-12.817-1.358-16.682a10.77 10.77 0 0 0-12.577.299L24 12.247z");
}

</style>
