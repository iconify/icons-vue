<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="m_w8dk51x"/><path class="c-btozl7c"/><path class="ayq1jkjxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:koge" /></template>
<style>
.ayq1jkjxz {
  fill: var(--svg-color--ffc700, #ffc700);
  d: path("m12.673 10.95l1.313.953l-1.07.689l1.345 1.064l2.504-1.467l-6.57-4.844l-1.37.81l2.646 1.922v1.615z");
}

.c-btozl7c {
  fill: var(--svg-color--2c2e35, #2c2e35);
  d: path("M8.824 8.184v8.56l1.588-.846v-6.83zm2.647 5.284l1.197.91l-1.197.794z");
}

.ft5dv1b6b {
  fill: none;
}

.m_w8dk51x {
  fill: var(--svg-color--ffc800, #ffc800);
  fill-rule: evenodd;
  d: path("M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18m0-1.059a7.942 7.942 0 1 0 0-15.883a7.942 7.942 0 0 0 0 15.883");
}

</style>
