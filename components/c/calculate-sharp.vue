<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejwlpj2bw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:calculate-sharp" /></template>
<style>
.ejwlpj2bw {
  fill: currentColor;
  d: path("M8 18h1.5v-2h2v-1.5h-2v-2H8v2H6V16h2zm5-.75h5v-1.5h-5zm0-2.5h5v-1.5h-5zM6.25 9.2h5V7.7h-5zM3 21V3h18v18zm11.1-10.05l1.4-1.4l1.4 1.4l1.05-1.05l-1.4-1.45l1.4-1.4L16.9 6l-1.4 1.4L14.1 6l-1.05 1.05l1.4 1.4l-1.4 1.45z");
}

</style>
