<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx1qacbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fit-screen-outline-sharp" /></template>
<style>
.lx1qacbxp {
  fill: currentColor;
  d: path("M20 9V6h-3V4h5v5zM2 9V4h5v2H4v3zm15 11v-2h3v-3h2v5zM2 20v-5h2v3h3v2zm4-4V8h12v8zm2-2h8v-4H8zm0 0v-4z");
}

</style>
