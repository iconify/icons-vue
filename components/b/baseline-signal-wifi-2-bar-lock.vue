<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpa4zjbgw"/><path class="bxixdwdoe"/><path class="y-4uo7b0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-signal-wifi-2-bar-lock" /></template>
<style>
.bxixdwdoe {
  fill: currentColor;
  d: path("M15.5 14.5c0-2.8 2.2-5 5-5c.4 0 .7 0 1 .1L23.6 7c-.4-.3-4.9-4-11.6-4S.8 6.7.4 7L12 21.5l3.5-4.3z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.xpa4zjbgw {
  fill: currentColor;
  d: path("M23 16v-1.5c0-1.4-1.1-2.5-2.5-2.5S18 13.1 18 14.5V16c-.5 0-1 .5-1 1v4c0 .5.5 1 1 1h5c.5 0 1-.5 1-1v-4c0-.5-.5-1-1-1m-1 0h-3v-1.5c0-.8.7-1.5 1.5-1.5s1.5.7 1.5 1.5z");
}

.y-4uo7b0k {
  fill: currentColor;
  d: path("m4.8 12.5l7.2 9l3.5-4.4v-2.6c0-1.3.5-2.5 1.4-3.4C15.6 10.5 14 10 12 10c-4.1 0-6.8 2.2-7.2 2.5");
}

</style>
