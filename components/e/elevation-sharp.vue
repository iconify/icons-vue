<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rad-i6bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:elevation-sharp" /></template>
<style>
.rad-i6bxc {
  fill: currentColor;
  d: path("m2.05 21l6.45-9h5.05L21 3.3V21zm1.75-5.825l-1.6-1.15L6.5 8h5.05l4.7-5.475l1.5 1.3L12.45 10H7.5z");
}

</style>
