<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9-upsb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-phone-corner" /></template>
<style>
.z9-upsb_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 21H6a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v2M8 3v2m8-2v2M4 9h16m-7 4.889c0-.491.398-.889.889-.889h1.333c.443 0 .8.179.89.444l.444 1.334c.068.204-.104.548-.445.889l-.444.444a.63.63 0 0 0 0 .889L17 18.333a.63.63 0 0 0 .889 0l.444-.444c.34-.34.685-.513.89-.445l1.333.445c.265.088.444.446.444.889v1.333a.89.89 0 0 1-.889.889A7.11 7.11 0 0 1 13 13.889");
}

</style>
