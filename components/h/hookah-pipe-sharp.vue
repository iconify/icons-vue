<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz_l93_lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hookah-pipe-sharp" /></template>
<style>
.zz_l93_lt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 13.25c2.75 0 4.5 2.4 4.5 4.6a3.4 3.4 0 0 1-3.4 3.4h-2.2a3.4 3.4 0 0 1-3.4-3.4c0-2.2 1.75-4.6 4.5-4.6Zm-1.9-9h4.4l-.25.55l-.75 1.65l-.25.55h-2.5l-.25-.55l-.75-1.65l-.25-.55zM12 7v6.25m0-2.5c2.25 0 3-2.5 5.25-2.5c1.75 0 3 1.25 3 3.25v3m0 2v2.75");
}

</style>
