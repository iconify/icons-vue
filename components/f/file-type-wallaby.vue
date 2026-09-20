<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j8izj1sfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-wallaby" /></template>
<style>
.j8izj1sfb {
  fill: var(--svg-color--5fb050, #5fb050);
  d: path("M2 16h14V2h14v28H2Z");
}

</style>
