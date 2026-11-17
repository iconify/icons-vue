<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3o562bla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:devices-code-corner-fill" /></template>
<style>
.k3o562bla {
  fill: currentColor;
  d: path("M19.001 14H17a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3v6a3 3 0 0 1-2.999 3M4 6v8a.997.997 0 0 0 1 1h5a1 1 0 0 1 0 2H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h6a1 1 0 0 1 0 2H5a.997.997 0 0 0-1 1m11.707 11.707L14.414 19l1.293 1.293a.999.999 0 1 1-1.414 1.414l-2-2a1 1 0 0 1 0-1.414l2-2a.999.999 0 1 1 1.414 1.414m4-1.414l2 2a1 1 0 0 1 0 1.414l-2 2a.999.999 0 1 1-1.414-1.414L19.586 19l-1.293-1.293a.999.999 0 1 1 1.414-1.414");
}

</style>
