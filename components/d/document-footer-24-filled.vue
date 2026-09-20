<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ontc-ry_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-footer-24-filled" /></template>
<style>
.ontc-ry_v {
  fill: currentColor;
  d: path("M17.746 1.996a2.25 2.25 0 0 1 2.245 2.096l.005.154v15.498A2.25 2.25 0 0 1 17.9 21.99l-.154.005h-11.5a2.25 2.25 0 0 1-2.245-2.096l-.005-.154V4.246a2.25 2.25 0 0 1 2.096-2.245l.154-.005zM8.501 16a1.5 1.5 0 0 0 0 3h7a1.5 1.5 0 0 0 0-3z");
}

</style>
