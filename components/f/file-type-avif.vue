<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m_eh6nd0v"/><path class="hdkvk5pkr"/><path class="ise_1-b0m"/><path class="hr58w3xlx"/><path class="ih51e02_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-avif" /></template>
<style>
.hdkvk5pkr {
  fill: var(--svg-color--12b17d, #12b17d);
  d: path("m29.913 20.149l-2.408-2.775h-8.022l-2.416 2.775Z");
}

.hr58w3xlx {
  d: path("M8.309 19.138H5.258l-.3 1.02H2.345l2.923-7.939H8.3l2.922 7.939h-2.6Zm-2.435-2h1.82l-.91-2.794Zm3.768-4.916h2.729l1.709 5.339l1.709-5.339h2.729L15.6 20.158h-3.036l-2.922-7.939");
}

.ih51e02_r {
  fill: var(--svg-color--f1f4d4, #f1f4d4);
  d: path("m23.03 14.213l-.827.827l-.891-.938l1.93-1.883h1.35v4.769H23.03Z");
}

.ise_1-b0m {
  fill: var(--svg-color--bb255c, #bb255c);
  d: path("m23.481 24.33l4.024-6.956h-8.022Z");
}

.m_eh6nd0v {
  fill: var(--svg-color--fbac30, #fbac30);
  d: path("M29.913 20.149L23.481 9.03l-6.414 11.119Z");
}

</style>
