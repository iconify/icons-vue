<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3e4v489a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:language-us-colemak-outline-sharp" /></template>
<style>
.p3e4v489a {
  fill: currentColor;
  d: path("M13.577 15.5H18v-7h-4.423zM5 16.5v-9h5.577v1H6v7h4.577v1zm7.577 0v-9H19v9z");
}

</style>
