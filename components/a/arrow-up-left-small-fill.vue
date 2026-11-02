<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-qr-tb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-up-left-small-fill" /></template>
<style>
.u-qr-tb_l {
  fill: currentColor;
  d: path("m10.414 9l6.293 6.293a.999.999 0 1 1-1.414 1.414L9 10.414V14a1 1 0 0 1-2 0V8a1 1 0 0 1 1-1h6a1 1 0 0 1 0 2Z");
}

</style>
