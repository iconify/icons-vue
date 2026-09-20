<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#tokenBrandedBgb0)" class="kdy6qmd-z"/><defs><linearGradient id="tokenBrandedBgb0" x1="22" x2="2" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="bh7gmou-i"/><stop offset="1" class="gb_6nzbvw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bgb" /></template>
<style>
.bh7gmou-i {
  stop-color: var(--svg-color--008bce, #008BCE);
}

.ft5dv1b6b {
  fill: none;
}

.gb_6nzbvw {
  stop-color: var(--svg-color--1ba2b6, #1BA2B6);
}

.kdy6qmd-z {
  d: path("M2.364 8.188a1.296 1.296 0 0 0 0 1.8l5.49 5.648h3.607l-5.297-5.454h6.14L9.878 7.758H6.394l5.297-5.455H8.085zm15.557 7.448l-5.618 6.061h3.612l5.721-6.17a1.403 1.403 0 0 0 0-1.885l-5.454-5.884H12.57l5.06 5.454h-5.933l2.424 2.424z");
}

</style>
