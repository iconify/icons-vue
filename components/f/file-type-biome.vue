<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z3txnz2iv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-biome" /></template>
<style>
.z3txnz2iv {
  fill: var(--svg-color--60a5fa, #60a5fa);
  d: path("M16 3.903L9.777 14.68a14.04 14.04 0 0 1 7.364-.255l2.103.496l-1.979 8.39l-2.106-.496c-2.588-.61-5.076.749-6.127 2.918l-1.947-.942c1.486-3.068 4.987-4.926 8.572-4.08l.986-4.182A11.887 11.887 0 0 0 2.032 28.097H29.97z");
}

</style>
