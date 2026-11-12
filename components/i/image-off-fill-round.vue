<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n364bz6ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-off-fill-round" /></template>
<style>
.n364bz6ks {
  fill: currentColor;
  d: path("m2.707 1.293l20 20a.999.999 0 1 1-1.414 1.414l-1.535-1.535A5 5 0 0 1 17 22H7a4.99 4.99 0 0 1-4.584-3.001L10 11.414L8.586 10L2 16.586V7c0-.981.286-1.94.828-2.758L1.293 2.707a.999.999 0 1 1 1.414-1.414m19.244 16.415L6.292 2.049Q6.644 1.999 7 2h10a5 5 0 0 1 5 5v10q0 .356-.049.708M15.158 6.221a2 2 0 1 0 3.684 1.558a2 2 0 0 0-3.684-1.558");
}

</style>
