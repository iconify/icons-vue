<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekjmdtzjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:grid-on-outline-sharp" /></template>
<style>
.ekjmdtzjx {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h3.998v-3.998H5zm4.998 0h4.004v-3.998H9.998zm5.004 0H19v-3.998h-3.998zM5 14.002h3.998V9.998H5zm4.998 0h4.004V9.998H9.998zm5.004 0H19V9.998h-3.998zM5 8.998h3.998V5H5zm4.998 0h4.004V5H9.998zm5.004 0H19V5h-3.998z");
}

</style>
