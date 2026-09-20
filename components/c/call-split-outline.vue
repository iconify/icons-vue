<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izz2p3gix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:call-split-outline" /></template>
<style>
.izz2p3gix {
  fill: currentColor;
  d: path("M11.5 19v-6.792L6 6.708V10H5V5h5v1H6.708l5.792 5.792V19zm2.658-8.439l-.72-.719L17.293 6H14V5h5v5h-1V6.708z");
}

</style>
