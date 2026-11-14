<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="am0x9xb5v"/><path class="kq-ckrb1u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:digital-music-stand" /></template>
<style>
.am0x9xb5v {
  d: path("M4 2.5h16V15H4ZM12 15v3l-4.5 3.5M12 18l4.5 3.5M13 5.25v5.5");
}

.kq-ckrb1u {
  d: path("M10 10.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm3-5.5l2.5 1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
