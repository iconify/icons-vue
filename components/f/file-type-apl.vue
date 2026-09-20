<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a423g1baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-apl" /></template>
<style>
.a423g1baw {
  fill: var(--svg-color--d2d2d2, #d2d2d2);
  d: path("M30 28.275L16 2L2 28.275h12.162V30h3.676v-1.725Zm-12.162-3.449V13.161l6.215 11.665Zm-9.891 0l6.215-11.665v11.665Z");
}

</style>
