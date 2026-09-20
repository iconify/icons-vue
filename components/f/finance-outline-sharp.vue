<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2ftrtbih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:finance-outline-sharp" /></template>
<style>
.k2ftrtbih {
  fill: currentColor;
  d: path("M3.5 20V3h1v16h16v1zm3.885-3.5V9.192h2V16.5zm4.5 0V4.192h2V16.5zm4.5 0v-3.308h2V16.5z");
}

</style>
