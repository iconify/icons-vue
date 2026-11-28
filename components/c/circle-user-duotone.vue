<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f1x3syyrx"/><path clip-rule="evenodd" class="x8k-8c-qh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-user-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f1x3syyrx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 12C23 18.075 18.075 23 12 23C5.925 23 1 18.075 1 12C1 5.925 5.925 1 12 1C18.075 1 23 5.925 23 12Z");
}

.x8k-8c-qh {
  fill-rule: evenodd;
  d: path("M15 9C15 10.657 13.657 12 12 12C10.343 12 9 10.657 9 9C9 7.343 10.343 6 12 6C13.657 6 15 7.343 15 9ZM13 14C15.665 14 17.842 16.086 18 18.708C16.35 20.184 14.214 21 12 21C9.786 21 7.65 20.184 6 18.708C6.157 16.086 8.335 14 11 14H13Z");
}

</style>
