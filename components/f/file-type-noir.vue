<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rd4vukbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-noir" /></template>
<style>
.rd4vukbue {
  fill: var(--svg-color--d2d2d2, #d2d2d2);
  d: path("M2.58 30h11.1V12.92c0-1.26.9-2.17 2.34-2.17c1.18 0 2.3.9 2.3 2.17V30h11.1V3.78c0-.98-.8-1.78-1.78-1.78H2.58z");
}

</style>
