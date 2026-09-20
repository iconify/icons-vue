<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd5_dqb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:art-track-sharp" /></template>
<style>
.nd5_dqb2z {
  fill: currentColor;
  d: path("M13.77 18h-12V6h12zM17 18V6h1v12zm4.23 0V6h1v12zm-17-3.23h7.078l-2.139-2.886l-1.9 2.5l-1.4-1.85z");
}

</style>
