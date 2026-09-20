<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brdbo4b4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bus-map-pin-sharp" /></template>
<style>
.brdbo4b4b {
  fill: currentColor;
  d: path("M8.293 16.289q.323-.327.323-.794q0-.466-.327-.788q-.327-.323-.793-.323q-.467 0-.79.327q-.322.327-.322.793q0 .467.327.79q.327.322.793.322q.467 0 .79-.327m7 0q.321-.327.321-.794q0-.466-.326-.788q-.327-.323-.794-.323q-.466 0-.788.327q-.323.327-.323.793q0 .467.327.79q.327.322.793.322q.467 0 .79-.327M5.538 21v-2.396q-.489-.212-1.014-.901T4 16.115V7q0-1.556 1.684-2.278Q7.37 4 11 4q.706 0 1.33.022t1.187.072q-.06.255-.087.497t-.026.505q0 .621.142 1.256q.143.635.389 1.187H5V12h11.787L18 13.125v2.99q0 .899-.525 1.588t-1.014.9V21h-1.23v-2H6.769v2zm14.04-15.233q.23-.233.23-.578t-.233-.575q-.234-.23-.578-.23q-.345 0-.575.234q-.23.233-.23.578t.233.574t.578.23t.575-.233M19 10.039q-1.621-1.38-2.426-2.573t-.805-2.2q0-1.37.932-2.337T19 1.962t2.299.967t.932 2.337q0 1.007-.805 2.2T19 10.04");
}

</style>
