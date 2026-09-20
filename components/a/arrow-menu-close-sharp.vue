<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7o_l_b5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-menu-close-sharp" /></template>
<style>
.z7o_l_b5v {
  fill: currentColor;
  d: path("M10.616 15.635v-7.25L7.135 12zM13 20h1V4h-1z");
}

</style>
