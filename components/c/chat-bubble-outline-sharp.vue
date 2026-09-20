<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftc1kcc1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chat-bubble-outline-sharp" /></template>
<style>
.ftc1kcc1p {
  fill: currentColor;
  d: path("M2 22V2h20v16H6zm3.15-6H20V4H4v13.125zM4 16V4z");
}

</style>
