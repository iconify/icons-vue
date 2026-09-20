<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rkgiwqbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-quokka" /></template>
<style>
.rkgiwqbgu {
  fill: var(--svg-color--fc6515, #fc6515);
  d: path("M2 16h14V2h14v28H2z");
}

</style>
