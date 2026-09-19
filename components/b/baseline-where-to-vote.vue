<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghdvi_b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-where-to-vote" /></template>
<style>
.ghdvi_b4d {
  fill: currentColor;
  d: path("M12 2c3.86 0 7 3.14 7 7c0 5.25-7 13-7 13S5 14.25 5 9c0-3.86 3.14-7 7-7m-1.53 12L17 7.41L15.6 6l-5.13 5.18L8.4 9.09L7 10.5z");
}

</style>
