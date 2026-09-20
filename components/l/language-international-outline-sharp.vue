<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rht-29q0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:language-international-outline-sharp" /></template>
<style>
.rht-29q0m {
  fill: currentColor;
  d: path("M2.27 15.5v-7h1v7zm2.615 0v-7h1.23l3.13 6.065l-.36.05V8.5h1v7H8.654L5.525 9.435l.36-.05V15.5zm8.423 0v-6h-2v-1h5v1h-2v6zm4.423 0v-7h1v6h3v1z");
}

</style>
