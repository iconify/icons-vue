<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvm4k6b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bookmark-flag-outline-sharp" /></template>
<style>
.hvm4k6b9z {
  fill: currentColor;
  d: path("M9.808 13.692h.884v-3h4.193L13.615 9l1.27-1.692H9.808zM6 19.5V4h12v15.5l-6-2.583zm1-1.55l5-2.15l5 2.15V5H7zM7 5h10z");
}

</style>
