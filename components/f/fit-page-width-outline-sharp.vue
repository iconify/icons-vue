<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="art4liv1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fit-page-width-outline-sharp" /></template>
<style>
.art4liv1x {
  fill: currentColor;
  d: path("M9 15V9l-3 3zm9-3l-3-3v6zM2 20V4h20v16zM20 6H4v12h16zM4 6v12z");
}

</style>
