<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jnodkfb6z"/><path class="pk1u_bbvu"/><path class="poon74vdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:container-store" /></template>
<style>
.jnodkfb6z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 15.083L36.9 31.95a1.52 1.52 0 0 1-1.418.968H12.519c-.628 0-1.19-.385-1.419-.968L4.5 15.083");
}

.pk1u_bbvu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m37.862 15.083l-4.604 11.632c-.221.557-.76.924-1.36.924H16.102c-.6 0-1.139-.367-1.36-.924l-4.604-11.632");
}

.poon74vdq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.224 15.083l-2.466 6.06a1.95 1.95 0 0 1-1.81 1.218h-7.896c-.795 0-1.51-.481-1.81-1.218l-2.466-6.06");
}

</style>
