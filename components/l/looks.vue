<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="il06fxbjb"/><path class="f6hy16cbx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:looks" /></template>
<style>
.bi12bsetm {
  fill: none;
  fill-rule: evenodd;
}

.f6hy16cbx {
  fill: var(--svg-color--f0f3fa, #f0f3fa);
  d: path("M15 10.5a3 3 0 1 0-6 0a3 3 0 0 0 6.001 0m-1.5 0A1.5 1.5 0 0 0 12 9c-.835 0-1.5.665-1.5 1.5S11.165 12 12 12s1.5-.665 1.5-1.5");
}

.il06fxbjb {
  fill: var(--svg-color--04cd58, #04cd58);
  d: path("M21 10.25L15.6 5H8.4L3 10.25L12 19zm-2.5.25s-5.98-9-13 0c7 9 13 0 13 0");
}

</style>
