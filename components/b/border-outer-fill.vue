<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqr2epu8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:border-outer-fill" /></template>
<style>
.uqr2epu8z {
  fill: currentColor;
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm10.01 1H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2m-5 5H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M12 11a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm5.01 0H17a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M12 16a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>
