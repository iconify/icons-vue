<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="a8_mfvb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:align-bottom-28-filled" /></template>
<style>
.a8_mfvb1j {
  fill: currentColor;
  d: path("M2.75 25a.75.75 0 0 1 0-1.5h22.5a.75.75 0 0 1 0 1.5zM5 19.25A2.75 2.75 0 0 0 7.75 22h2.5A2.75 2.75 0 0 0 13 19.25V5.75A2.75 2.75 0 0 0 10.25 3h-2.5A2.75 2.75 0 0 0 5 5.75zm10 0A2.75 2.75 0 0 0 17.75 22h2.5A2.75 2.75 0 0 0 23 19.25v-8a2.75 2.75 0 0 0-2.75-2.75h-2.5A2.75 2.75 0 0 0 15 11.25z");
}

</style>
