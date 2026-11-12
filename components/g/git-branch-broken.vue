<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="if7b_fg1p"/><path class="w6v4566pk"/><path class="vcufaui4b"/><path class="dm7s30bzj"/><path class="w77j1_bab"/><path class="zuwpoxb1z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:git-branch-broken" /></template>
<style>
.dm7s30bzj {
  d: path("M6.5 17L6.5 7");
}

.if7b_fg1p {
  d: path("M9 4.5C9 5.88071 7.88071 7 6.5 7C5.11929 7 4 5.88071 4 4.5C4 3.11929 5.11929 2 6.5 2C7.88071 2 9 3.11929 9 4.5Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vcufaui4b {
  d: path("M9 19.5C9 20.8807 7.88071 22 6.5 22C5.11929 22 4 20.8807 4 19.5C4 18.1193 5.11929 17 6.5 17C7.88071 17 9 18.1193 9 19.5Z");
}

.w6v4566pk {
  d: path("M20.1816 7.5C20.1816 8.88071 19.0624 10 17.6816 10C16.3009 10 15.1816 8.88071 15.1816 7.5C15.1816 6.11929 16.3009 5 17.6816 5C19.0624 5 20.1816 6.11929 20.1816 7.5Z");
}

.w77j1_bab {
  d: path("M17.6824 10C17.6824 11.8644 16.2642 13.0389 13.9844 13.4384");
}

.zuwpoxb1z {
  d: path("M9.99359 13.7593C7.83214 14.1447 6.5 15.2004 6.5 17");
}

</style>
