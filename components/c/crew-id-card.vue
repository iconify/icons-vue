<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qiywqf--f"/><path class="ja35hg10o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crew-id-card" /></template>
<style>
.ja35hg10o {
  d: path("M7.5 10.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-1 7c0-1.5 1.25-2.25 3-2.25s3 .75 3 2.25m3-7H18m-2.5 4H18");
}

.qiywqf--f {
  d: path("M3 5.5h18v15H3Zm7 0v-2a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
