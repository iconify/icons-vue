<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lzexiwb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lowes" /></template>
<style>
.lzexiwb3s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.569 21.808v-2.594h-6.33L24 14.722l-10.239 4.492H7.446v2.594H4.5v11.47h39v-11.47z");
}

</style>
