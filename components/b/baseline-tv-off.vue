<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l92-bt9qg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-tv-off" /></template>
<style>
.l92-bt9qg {
  fill: currentColor;
  d: path("m1 3.54l1.53 1.53C1.65 5.28 1 6.06 1 7v12c0 1.1.9 2 2 2h15.46l2 2l1.26-1.27L2.27 2.27zM3 19V7h1.46l12 12zM21 5h-7.58l3.29-3.3L16 1l-4 4l-4-4l-.7.7L10.58 5H7.52l2 2H21v11.48l1.65 1.65c.22-.32.35-.71.35-1.13V7c0-1.11-.89-2-2-2");
}

</style>
