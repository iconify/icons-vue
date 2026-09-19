<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="c57e54bsg"/><path class="l7_c1msje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:ballot-box-with-check" /></template>
<style>
.c57e54bsg {
  fill: var(--svg-color--405866, #405866);
  d: path("M64 57.1a6.895 6.895 0 0 1-6.897 6.898H6.893A6.897 6.897 0 0 1-.004 57.1V6.9A6.9 6.9 0 0 1 6.893.002h50.2A6.896 6.896 0 0 1 63.99 6.9v50.2");
}

.l7_c1msje {
  fill: var(--svg-color--f4f4f4, #f4f4f4);
  d: path("M54.04 14.186a4.67 4.67 0 0 0-6.582.516l-20.1 23.515l-10.815-9.03a4.27 4.27 0 0 0-6.01.538a4.26 4.26 0 0 0 .54 6l14.492 12.1a4.24 4.24 0 0 0 3.248.949a4.66 4.66 0 0 0 3.189-1.622l22.554-26.387a4.67 4.67 0 0 0-.516-6.581");
}

</style>
