<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynn154bjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bottom-panel-open-outline-sharp" /></template>
<style>
.ynn154bjo {
  fill: currentColor;
  d: path("M8 11.5h8l-4-4zM5 19h14v-3H5zm0-5h14V5H5zm0 2v3zm-2 5V3h18v18z");
}

</style>
