<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mex4ecc2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hide-image-outline-sharp" /></template>
<style>
.mex4ecc2p {
  fill: currentColor;
  d: path("m20 17.15l-1-1V5H7.85l-1-1H20zm.492 4.758L18.585 20H4V5.416L2.092 3.508L2.8 2.8l18.4 18.4zM7.5 16.5l1.962-2.577l1.75 2.116l1.517-1.889L5 6.421V19h12.579l-2.5-2.5zm3.792-3.792");
}

</style>
