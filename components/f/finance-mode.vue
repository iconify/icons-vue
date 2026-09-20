<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmdba20hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:finance-mode" /></template>
<style>
.dmdba20hn {
  fill: currentColor;
  d: path("M8 13.65V6h3v7.65l-1.5-1.4zm5 1.5V2h3v10.15zM3 18.6V10h3v5.6zm0 2.45l6.45-6.45L13 17.65l5.6-5.6H17v-2h5v5h-2v-1.6l-6.9 6.9l-3.55-3.05l-3.75 3.75z");
}

</style>
