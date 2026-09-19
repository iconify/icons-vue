<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp75p67iw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-send" /></template>
<style>
.bp75p67iw {
  fill: currentColor;
  d: path("M2.01 21L23 12L2.01 3L2 10l15 2l-15 2z");
}

</style>
