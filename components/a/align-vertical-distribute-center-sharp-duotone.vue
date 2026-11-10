<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fpwr0vasn"/><path class="qeyoeubpw"/><path class="hp59fzb1y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-vertical-distribute-center-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fpwr0vasn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 13C17.552 13 18 13.448 18 14V20C18 20.552 17.552 21 17 21H7C6.448 21 6 20.552 6 20V14C6 13.448 6.448 13 7 13H17ZM19 3C19.552 3 20 3.448 20 4V10C20 10.552 19.552 11 19 11H5C4.448 11 4 10.552 4 10V4C4 3.448 4.448 3 5 3H19Z");
}

.hp59fzb1y {
  d: path("M23 6V8H19V6H23Z");
}

.qeyoeubpw {
  d: path("M7 16V18H1V16H7ZM23 16V18H17V16H23ZM5 6V8H1V6H5Z");
}

</style>
