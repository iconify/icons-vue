<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2lb5s74q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hard-disk-sharp" /></template>
<style>
.p2lb5s74q {
  fill: currentColor;
  d: path("M5 21V3h14.02v18zm3.385-3.384h7.25v-1h-7.25zM12 14q1.592 0 2.7-1.108t1.108-2.7t-1.108-2.7T12 6.385T9.3 7.492t-1.108 2.7t1.108 2.7T12 14m.01-1.711q-.877 0-1.482-.615q-.605-.614-.605-1.482t.605-1.482t1.481-.614t1.492.602t.615 1.491t-.615 1.495t-1.491.605");
}

</style>
