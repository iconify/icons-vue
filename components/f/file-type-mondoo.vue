<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="szank4bge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-mondoo" /></template>
<style>
.szank4bge {
  fill: var(--svg-color--6e45e2, #6e45e2);
  d: path("M9.03 9.03A6.97 6.97 0 0 0 2.06 16a6.97 6.97 0 0 0 6.97 6.97zm0 6.97A6.97 6.97 0 0 0 16 22.97A6.97 6.97 0 0 0 22.97 16A6.97 6.97 0 0 0 16 9.03A6.97 6.97 0 0 0 9.03 16m13.941 0v6.969A6.97 6.97 0 0 0 29.94 16a6.97 6.97 0 0 0-6.969-6.97z");
}

</style>
