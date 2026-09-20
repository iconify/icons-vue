<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="iq3wgyeez"/><path class="o1doedbhf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:conv" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iq3wgyeez {
  fill: var(--svg-color--342989, #342989);
  d: path("m19.71 7.358l-4.685 4.64l4.68 4.65A8.95 8.95 0 0 0 21 11.998c0-1.7-.47-3.285-1.29-4.64");
}

.o1doedbhf {
  fill: var(--svg-color--e31c38, #e31c38);
  d: path("m18.41 5.683l-2.13 2.11a6 6 0 1 0 0 8.414l2.125 2.115a9 9 0 1 1 .005-12.64");
}

</style>
