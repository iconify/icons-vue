<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="sbpa2mbvx"/><path class="g3v5g6bjk"/><path class="sk4y64bwi"/><path class="uunvf9fht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-flag-chile" /></template>
<style>
.g3v5g6bjk {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M54 10H23v22h41V21c0-6.075-3.373-11-10-11");
}

.sbpa2mbvx {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M0 32v11c0 6.075 3.373 11 10 11h44c6.627 0 10-4.925 10-11V32z");
}

.sk4y64bwi {
  fill: var(--svg-color--2b3990, #2b3990);
  d: path("M23 10H10C3.373 10 0 14.925 0 21v11h23z");
}

.uunvf9fht {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("m11.52 13.997l2.247 4.554l5.03.739l-3.638 3.548l.86 5l-4.5-2.364l-4.5 2.364l.86-5L4.24 19.29l5.03-.739z");
}

</style>
