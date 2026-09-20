<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xtxz4qb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:cassette-tape" /></template>
<style>
.xtxz4qb6s {
  fill: currentColor;
  d: path("M224 48H32a16 16 0 0 0-16 16v128a16 16 0 0 0 16 16h192a16 16 0 0 0 16-16V64a16 16 0 0 0-16-16M80 192l12-16h72l12 16Zm144 0h-28l-21.6-28.8a8 8 0 0 0-6.4-3.2H88a8 8 0 0 0-6.4 3.2L60 192H32V64h192zM176 80H80a32 32 0 0 0 0 64h96a32 32 0 0 0 0-64m-27.7 16a31.92 31.92 0 0 0 0 32h-40.6a31.92 31.92 0 0 0 0-32ZM64 112a16 16 0 1 1 16 16a16 16 0 0 1-16-16m112 16a16 16 0 1 1 16-16a16 16 0 0 1-16 16");
}

</style>
