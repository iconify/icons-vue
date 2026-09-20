<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_fd2_g3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:home-improvement-and-tools" /></template>
<style>
.v_fd2_g3j {
  fill: currentColor;
  d: path("M7.962 3h8.076L14 5.892V10.5h-4V5.892zM10 11.5h4v3h-4zm0 4h4v3.077l-2 2l-2-2z");
}

</style>
