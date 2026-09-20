<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwhfckbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:branding-watermark-outline-sharp" /></template>
<style>
.pwhfckbzl {
  fill: currentColor;
  d: path("M10 17h9v-6h-9zm-8 3V4h20v16zm2-2h16V6H4zm0 0V6z");
}

</style>
