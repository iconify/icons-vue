<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_q9m8b0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-app-registration" /></template>
<style>
.n_q9m8b0p {
  fill: currentColor;
  d: path("M10 4h4v4h-4zM4 16h4v4H4zm0-6h4v4H4zm0-6h4v4H4zm10 8.42V10h-4v4h2.42zm6.88-1.13l-1.17-1.17a.41.41 0 0 0-.58 0l-.88.88L20 12.75l.88-.88a.41.41 0 0 0 0-.58M11 18.25V20h1.75l6.67-6.67l-1.75-1.75zM16 4h4v4h-4z");
}

</style>
