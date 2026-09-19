<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o0fqleb5a"/><path class="xmydfabif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cmrl" /></template>
<style>
.o0fqleb5a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.417 31.42c-4.686 7.6-14.867 10.094-22.74 5.57c-7.872-4.525-10.454-14.355-5.768-21.957c4.686-7.6 14.867-10.094 22.74-5.57a16.4 16.4 0 0 1 5.172 4.674");
}

.xmydfabif {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.408 30.836c-12.59-2.3-17.378-7.485-18.581-15.544L21.43 23.35l-5.384-8.058v15.544l29.453.132c-3.876 11.23-16.386 17.214-27.942 13.365S-.224 28.262 3.652 17.032S20.038-.182 31.594 3.667c5.53 1.842 10.102 5.737 12.715 10.833");
}

</style>
