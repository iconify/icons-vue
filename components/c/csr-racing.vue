<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q06u-5bks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:csr-racing" /></template>
<style>
.q06u-5bks {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.038 17.601C5.804 16.258.891 26.162 7.631 30.177c.737.44 1.662.335 2.406.335h10.212c2.924 0 4.008-1.172 4.475-3.182c.434-1.862-1.079-2.612-2.74-3.3c-2.384-.986-2.994-1.77-2.562-3.566c.334-1.388 1.447-2.412 2.898-2.42h8.312m-.197 12.468l4.002-12.468h6.025c2.016 0 3.087.672 3.036 2.345c-.052 1.712-1.61 3.647-3.176 3.645h-2.267l1.31 6.478");
}

</style>
