<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k8vqq7c1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-gamemaker2" /></template>
<style>
.k8vqq7c1x {
  fill: var(--svg-color--c2c2c2, #c2c2c2);
  d: path("M16.011 2L30 16c-2.7 0-5.394.005-8.09 0v8.112c-1.96 1.965-3.928 3.922-5.885 5.888L2 16.008ZM10.12 16.008l5.889 5.892V16c1.96 0 3.92.005 5.88 0c-1.949-1.973-3.92-3.925-5.878-5.888q-2.947 2.946-5.891 5.896");
}

</style>
