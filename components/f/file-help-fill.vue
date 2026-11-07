<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gf1om9bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-help-fill" /></template>
<style>
.gf1om9bjv {
  fill: currentColor;
  d: path("M19.707 8.293A1 1 0 0 1 20 9v10a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h6c.265 0 .52.105.707.293ZM13 7a2 2 0 0 0 2 2h3l-5-5Zm-5 6a1 1 0 0 0 2 0a1.001 1.001 0 0 1 1.707-.707a1 1 0 0 1 .215 1.094A.99.99 0 0 1 11 14a1 1 0 0 0 0 2a3 3 0 1 0-3-3m3.01 4H11a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
