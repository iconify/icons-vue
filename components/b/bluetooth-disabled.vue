<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3lyhizhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:bluetooth-disabled" /></template>
<style>
.k3lyhizhk {
  fill: currentColor;
  d: path("m13 5.83l1.88 1.88l-1.6 1.6l1.41 1.41l3.02-3.02L12 2h-1v5.03l2 2zM5.41 4L4 5.41L10.59 12L5 17.59L6.41 19L11 14.41V22h1l4.29-4.29l2.3 2.29L20 18.59zM13 18.17v-3.76l1.88 1.88z");
}

</style>
