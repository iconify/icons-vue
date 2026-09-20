<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xg-rh6avq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-insert-rounded" /></template>
<style>
.xg-rh6avq {
  fill: currentColor;
  d: path("M7.712 7.208V16q0 .213-.144.356q-.144.144-.357.144t-.356-.144T6.71 16V6.308q0-.343.233-.576t.575-.232h9.693q.212 0 .356.144t.143.357t-.143.356t-.357.143H8.42l9.747 9.766q.14.14.13.344t-.15.344t-.334.14t-.335-.14z");
}

</style>
