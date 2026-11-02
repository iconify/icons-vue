<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_7en6_pz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:camera-fill" /></template>
<style>
.f_7en6_pz {
  fill: currentColor;
  d: path("m6.586 6l1.707-1.707C9.008 3.578 9.961 3 11 3h2c1.039 0 1.992.578 2.707 1.293L17.414 6H19a3 3 0 0 1 3 3v9a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3Zm1.729 5.443a4 4 0 1 0 7.37 3.114a4 4 0 0 0-7.37-3.114");
}

</style>
