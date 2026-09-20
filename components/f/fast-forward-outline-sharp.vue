<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxz10ebwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fast-forward-outline-sharp" /></template>
<style>
.kxz10ebwg {
  fill: currentColor;
  d: path("M2.5 18V6l9 6zm10 0V6l9 6zm-8-3.75L7.9 12L4.5 9.75zm10 0L17.9 12l-3.4-2.25z");
}

</style>
