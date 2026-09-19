<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vlv0bob9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:firstcry" /></template>
<style>
.vlv0bob9u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.73 18.541c-4.405-5.422-12.096-1.668-10.884 7.653c.914 7.035 11.654 11.647 12.588 5.905M9.566 21.849c4.1 1.461 7.926 2.76 11.784 2.834m5.788-18.262c-5.07-5.199-10.834.997-10.976 8.551c-.163 8.693 1.24 19.01 1.873 28.528");
}

</style>
