<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkbteibjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:book-open-2" /></template>
<style>
.xkbteibjr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 6L4 6C3.4477 6 3 6.4477 3 7L3 18C3 18.5523 3.4477 19 4 19C7.1102 19 10.1825 19.6827 13 21C14.731 19.7018 16.8363 19 19 19C20.1046 19 21 18.1046 21 17L21 7C21 5.8954 20.1046 5 19 5C18.8967 5 18.7936 5.008 18.6915 5.0239C16.5187 5.3632 14.5183 6.4092 13 8C12.2613 5.7539 10.5668 3.9496 8.3714 3.0715C8.2532 3.0243 8.1272 3 8 3C7.4477 3 7 3.4477 7 4L7 15C7 15.5523 7.4477 16 8 16C10.7614 16 13 18.2386 13 21M13 8L13 21");
}

</style>
