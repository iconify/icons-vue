<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p98urxskq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-play-fill-round" /></template>
<style>
.p98urxskq {
  fill: currentColor;
  d: path("M2.786 8.107C4.936 3.02 10.804.639 15.892 2.788s7.469 8.016 5.32 13.104s-8.016 7.469-13.104 5.32S.637 13.195 2.786 8.107M9 10v4c0 .428.121.845.355 1.204c.699 1.07 2.146 1.33 3.2.628l3-2a2.202 2.202 0 0 0 0-3.664l-3-2c-1.054-.702-2.501-.442-3.2.628A2.2 2.2 0 0 0 9 10");
}

</style>
