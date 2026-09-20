<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="pmy_o-blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:folder-simple-dashed" /></template>
<style>
.pmy_o-blo {
  fill: currentColor;
  d: path("M24 80V64a16 16 0 0 1 16-16h53.33a16.12 16.12 0 0 1 9.6 3.2l29.87 22.4a8 8 0 1 1-9.6 12.8L93.33 64H40v16a8 8 0 0 1-16 0m64 120H40v-8a8 8 0 0 0-16 0v8.62A15.4 15.4 0 0 0 39.38 216H88a8 8 0 0 0 0-16m72 0h-32a8 8 0 0 0 0 16h32a8 8 0 0 0 0-16m64-56a8 8 0 0 0-8 8v48h-16a8 8 0 0 0 0 16h16.89A15.13 15.13 0 0 0 232 200.89V152a8 8 0 0 0-8-8m-8-72h-48a8 8 0 0 0 0 16h48v24a8 8 0 0 0 16 0V88a16 16 0 0 0-16-16M32 160a8 8 0 0 0 8-8v-32a8 8 0 0 0-16 0v32a8 8 0 0 0 8 8");
}

</style>
