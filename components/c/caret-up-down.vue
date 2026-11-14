<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4boh6kun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:caret-up-down" /></template>
<style>
.e4boh6kun {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.673 5.237q-.67-.745-1.672-.745t-1.672.745L9.192 6.498q-.976 1.085-.382 2.418q.593 1.333 2.053 1.334h2.274q1.46-.001 2.053-1.334q.594-1.333-.383-2.418zm0 13.526q-.67.745-1.672.745t-1.672-.745l-1.136-1.261q-.976-1.085-.382-2.418q.593-1.333 2.053-1.334h2.274q1.46.001 2.053 1.334q.594 1.333-.383 2.418z");
}

</style>
