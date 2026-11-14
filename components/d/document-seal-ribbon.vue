<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ojmdx_bwl"/><path class="wg72yabzp"/><path class="ovdfh3bwn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:document-seal-ribbon" /></template>
<style>
.ojmdx_bwl {
  d: path("M11.6 18.25H4v-16h12.5v6.4M7 6.25h6m-6 3.5h4");
}

.ovdfh3bwn {
  d: path("M15 17.5v3.25l1.5-1l1.5 1V17.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wg72yabzp {
  d: path("M13.25 14.75a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

</style>
