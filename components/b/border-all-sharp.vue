<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b84_blbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:border-all-sharp" /></template>
<style>
.b84_blbea {
  fill: currentColor;
  d: path("M12.5 20v-7.5H20V20zm0-8.5V4H20v7.5zm-8.5 0V4h7.5v7.5zM4 20v-7.5h7.5V20z");
}

</style>
