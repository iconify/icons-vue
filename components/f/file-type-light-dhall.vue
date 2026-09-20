<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="edqjt4b8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-dhall" /></template>
<style>
.edqjt4b8n {
  fill: var(--svg-color--484848, #484848);
  fill-rule: evenodd;
  d: path("M15.91 2a14 14 0 1 1-14 14a14 14 0 0 1 14-14m-2.69 20.3a1.5 1.5 0 1 1-1.06 1.83a1.5 1.5 0 0 1 1.06-1.83m8.07-15.73a.55.55 0 0 1 .38.66a.53.53 0 0 1-.66.38l-.5-.13a44 44 0 0 0-.37 7.09c-2.13 1.84-5.81 7.36-5.81 7.36l1.93-7.21a1 1 0 0 0 .9-.65a.9.9 0 1 0-1.75-.46a1 1 0 0 0 .45 1l-1.93 7.21a68 68 0 0 0-1.35-9.27a34.4 34.4 0 0 0 3.23-6.33l-.5-.14a.52.52 0 0 1-.38-.65a.54.54 0 0 1 .66-.43l5.7 1.53Z");
}

</style>
