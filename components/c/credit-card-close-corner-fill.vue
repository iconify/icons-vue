<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yv155qbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-close-corner-fill" /></template>
<style>
.yv155qbbi {
  fill: currentColor;
  d: path("M22 7v1H2V7a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3M2 10h8v9a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3Zm12.707 3.293L17 15.586l2.293-2.293a.999.999 0 1 1 1.414 1.414L18.414 17l2.293 2.293a.999.999 0 1 1-1.414 1.414L17 18.414l-2.293 2.293a.999.999 0 1 1-1.414-1.414L15.586 17l-2.293-2.293a.999.999 0 1 1 1.414-1.414");
}

</style>
