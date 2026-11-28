<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dqny1rzma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-devvit" /></template>
<style>
.dqny1rzma {
  fill: var(--svg-color--ff4500, #ff4500);
  d: path("M10.456 12.608L4.964 9.396a.774.774 0 0 1-.275-1.06a.8.8 0 0 1 .288-.28l10.614-5.92a.91.91 0 0 1 .89 0l10.615 5.921a.774.774 0 0 1 .297 1.054a.8.8 0 0 1-.282.285l-5.494 3.212l-5.182-2.99a.8.8 0 0 0-.798 0zm-.603 7.951a1.17 1.17 0 0 1-.582-1.015v-5.107l-5.156-3.018a.777.777 0 0 0-1.059.28a.75.75 0 0 0-.104.387V23.3a.9.9 0 0 0 .463.79l10.378 5.791a.775.775 0 0 0 1.152-.673v-5.715zm12.869-1.077a1.16 1.16 0 0 1-.582 1.015l-5.089 2.936v5.714a.76.76 0 0 0 .382.665a.77.77 0 0 0 .77.008l10.38-5.79a.9.9 0 0 0 .464-.804V12.01a.77.77 0 0 0-.389-.667a.77.77 0 0 0-.774.002l-5.162 3.017z");
}

</style>
