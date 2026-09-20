<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rma9l8b8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:curtains-closed" /></template>
<style>
.rma9l8b8a {
  fill: currentColor;
  d: path("M3 20v-1h2V4h14v15h2v1zm7.75-1h2.5V5h-2.5z");
}

</style>
