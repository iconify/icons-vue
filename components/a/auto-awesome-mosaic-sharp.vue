<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwwt_xfna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:auto-awesome-mosaic-sharp" /></template>
<style>
.mwwt_xfna {
  fill: currentColor;
  d: path("M11 21H3V3h8zm2-10V3h8v8zm0 10v-8h8v8z");
}

</style>
