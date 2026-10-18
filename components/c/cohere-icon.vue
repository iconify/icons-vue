<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":263};
const content = `<path class="hk7endbte"/><path class="k_5y59oft"/><path class="xzy-8h02f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:cohere-icon" /></template>
<style>
.hk7endbte {
  fill: var(--svg-color--355146, #355146);
  d: path("M82.937 156.277c6.89 0 20.596-.389 39.541-8.385c22.077-9.32 66.001-26.238 97.685-43.615c22.16-12.154 31.874-28.23 31.874-49.877c0-30.044-23.754-54.4-53.056-54.4H76.209C34.119 0 0 34.984 0 78.138s31.946 78.139 82.937 78.139");
}

.k_5y59oft {
  fill: var(--svg-color--d18ee2, #d18ee2);
  d: path("M103.707 210.119c0-21.154 12.42-40.227 31.476-48.336l38.664-16.451C212.955 128.69 256 158.157 256 201.572c0 33.636-26.599 60.9-59.405 60.891l-41.86-.011c-28.184-.007-51.028-23.435-51.028-52.333");
}

.xzy-8h02f {
  fill: var(--svg-color--ff7759, #ff7759);
  d: path("M43.932 166.556C19.669 166.556 0 186.723 0 211.6v5.835c0 24.877 19.669 45.043 43.932 45.043s43.932-20.166 43.932-45.043V211.6c0-24.877-19.669-45.044-43.932-45.044");
}

</style>
