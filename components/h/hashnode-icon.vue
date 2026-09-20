<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="mdx7rczvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:hashnode-icon" /></template>
<style>
.mdx7rczvg {
  fill: var(--svg-color--2962ff, #2962ff);
  fill-rule: evenodd;
  d: path("M17.591 85.533c-23.455 23.455-23.455 61.479 0 84.932l67.943 67.944c23.455 23.453 61.479 23.453 84.932 0l67.944-67.944c23.453-23.455 23.453-61.48 0-84.932L170.466 17.59c-23.455-23.452-61.48-23.452-84.932 0zm140.134 72.193c16.418-16.419 16.418-43.036 0-59.452c-16.417-16.419-43.034-16.419-59.45 0c-16.419 16.418-16.419 43.033 0 59.452c16.418 16.416 43.033 16.416 59.452 0z");
}

</style>
