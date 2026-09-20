<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="yxe2wmpez"/><path class="zb6o8vbaw"/><path class="ppdlohb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:codrops" /></template>
<style>
.ppdlohb3d {
  fill: var(--svg-color--61aad4, #61AAD4);
  d: path("M100.532 82.518s25.074 40.828 25.074 55.701c0 11.857-5.545 26.123-25.074 26.123c-19.53 0-25.084-14.274-25.084-26.131c0-14.361 25.084-55.693 25.084-55.693");
}

.yxe2wmpez {
  fill: var(--svg-color--237dac, #237DAC);
  d: path("M256 128c0 70.692-57.308 128-128 128C57.307 256 0 198.692 0 128C0 57.307 57.307 0 128 0c70.692 0 128 57.307 128 128");
}

.zb6o8vbaw {
  fill: var(--svg-color--fff, #FFF);
  d: path("M129.283 60.731s39.839 64.87 39.839 88.5c0 18.839-8.81 41.505-39.839 41.505c-31.029 0-39.854-22.679-39.854-41.517c0-22.818 39.854-88.488 39.854-88.488");
}

</style>
