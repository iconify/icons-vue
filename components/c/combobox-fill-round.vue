<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtxsslb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:combobox-fill-round" /></template>
<style>
.xtxsslb7w {
  fill: currentColor;
  d: path("M6 2h12a4 4 0 0 1 4 4v2a4 4 0 0 1-4 4H6a4 4 0 0 1-4-4V6a4 4 0 0 1 4-4m2 4a1 1 0 0 0-2 0v2a1 1 0 0 0 2 0Zm6.707-.707a.999.999 0 1 0-1.414 1.414l2 2a1 1 0 0 0 1.414 0l2-2a.999.999 0 1 0-1.414-1.414L16 6.586ZM5 14h14a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-2a3 3 0 0 1 3-3m12 3H7a1 1 0 0 0 0 2h10a1 1 0 0 0 0-2");
}

</style>
