<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xv7_zeblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:desktop-tower-bold" /></template>
<style>
.xv7_zeblo {
  fill: currentColor;
  d: path("M168 76a12 12 0 0 1 12-12h24a12 12 0 0 1 0 24h-24a12 12 0 0 1-12-12m12 48h24a12 12 0 0 0 0-24h-24a12 12 0 0 0 0 24m72-76v160a20 20 0 0 1-20 20h-80a20 20 0 0 1-20-20v-16h-32v12h8a12 12 0 0 1 0 24H68a12 12 0 0 1 0-24h8v-12H32a28 28 0 0 1-28-28V96a28 28 0 0 1 28-28h100V48a20 20 0 0 1 20-20h80a20 20 0 0 1 20 20M132 168V92H32a4 4 0 0 0-4 4v68a4 4 0 0 0 4 4Zm96-116h-72v152h72Zm-36 108a16 16 0 1 0 16 16a16 16 0 0 0-16-16");
}

</style>
