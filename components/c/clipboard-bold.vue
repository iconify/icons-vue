<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ee0x1dn7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:clipboard-bold" /></template>
<style>
.ee0x1dn7d {
  fill: currentColor;
  d: path("M200 28h-34.53a51.88 51.88 0 0 0-74.94 0H56a20 20 0 0 0-20 20v168a20 20 0 0 0 20 20h144a20 20 0 0 0 20-20V48a20 20 0 0 0-20-20m-44.29 32h-55.42a28 28 0 0 1 55.42 0M196 212H60V52h17.41A52 52 0 0 0 76 64v8a12 12 0 0 0 12 12h80a12 12 0 0 0 12-12v-8a52 52 0 0 0-1.41-12H196Z");
}

</style>
