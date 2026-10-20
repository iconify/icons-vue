<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="moi7l3bmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-function" /></template>
<style>
.moi7l3bmy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.4772 22 2 17.5228 2 12C2 6.4772 6.4772 2 12 2C17.5228 2 22 6.4772 22 12ZM8.1088 16.4893C8.4234 16.8174 8.8582 17.0029 9.3127 17.0029C10.0573 17.0029 10.7116 16.5094 10.9161 15.7934L13.0839 8.2066C13.2884 7.4906 13.9427 6.9971 14.6873 6.9971C15.1418 6.9971 15.5766 7.1826 15.8912 7.5107M10.0544 10.8882L14.5015 10.8882");
}

</style>
