<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rzqw1ltoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-serverless" /></template>
<style>
.rzqw1ltoy {
  fill: var(--svg-color--fd5750, #fd5750);
  fill-rule: evenodd;
  d: path("M2 22.419h4.956L5.42 27H2Zm0-8.709h7.875L8.34 18.29H2ZM2 5h10.794l-1.535 4.581H2Zm15.679 0H30v4.581H16.143Zm-4.455 13.291l1.536-4.581H30v4.581Zm-1.383 4.128H30V27H10.305Z");
}

</style>
