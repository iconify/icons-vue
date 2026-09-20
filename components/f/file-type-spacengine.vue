<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cqsms7hgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-spacengine" /></template>
<style>
.cqsms7hgb {
  fill: var(--svg-color--4780f5, #4780f5);
  d: path("M24 5h2v22h-2zm-5 4.409L6 13.941v2.13l13 5v-2.142L8.906 15.046L19 11.527z");
}

</style>
