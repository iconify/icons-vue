<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmk3vhwxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-play-circle-filled-white" /></template>
<style>
.lmk3vhwxs {
  fill: currentColor;
  d: path("M12 2C6.475 2 2 6.475 2 12s4.475 10 10 10s10-4.475 10-10S17.525 2 12 2m-2 14.5v-9l6 4.5z");
}

</style>
