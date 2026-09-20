<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c2jdlnuex"/><path class="tipnwl2gp"/><path class="i8ktz-kxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-appveyor" /></template>
<style>
.c2jdlnuex {
  fill: var(--svg-color--00b3e0, #00b3e0);
  d: path("M15.958 2a14 14 0 0 1 .091 28h-.091a14 14 0 0 1 0-28");
}

.i8ktz-kxt {
  fill: var(--svg-color--00b3e0, #00b3e0);
  d: path("M19.4 18.676a4.389 4.389 0 1 1-6.887-5.437a4.686 4.686 0 0 1 6.343-.815a4.36 4.36 0 0 1 .544 6.252");
}

.tipnwl2gp {
  fill: var(--svg-color--fff, #fff);
  d: path("m11.971 27.829l5.346-5.165a6.52 6.52 0 0 1-5.709-1.269a6.74 6.74 0 0 1-2.447-6.162l-4.8 5.256a9.3 9.3 0 0 1-.815-3.353l8.427-6.615a7.07 7.07 0 0 1 8.427 0a6.85 6.85 0 0 1 1.269 9.152l-6.169 8.79a11.6 11.6 0 0 1-3.534-.634Z");
}

</style>
