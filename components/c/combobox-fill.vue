<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="saij_wizs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:combobox-fill" /></template>
<style>
.saij_wizs {
  fill: currentColor;
  d: path("M5 2h14a3 3 0 0 1 3 3v4a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3m3 4a1 1 0 0 0-2 0v2a1 1 0 0 0 2 0Zm6.707-.707a.999.999 0 1 0-1.414 1.414l2 2a1 1 0 0 0 1.414 0l2-2a.999.999 0 1 0-1.414-1.414L16 6.586ZM4 14h16a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2m13 3H7a1 1 0 0 0 0 2h10a1 1 0 0 0 0-2");
}

</style>
