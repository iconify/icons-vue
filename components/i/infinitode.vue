<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tcpcsm4uz"/><path class="mp6tqxbcn"/><path class="e73y3rbuu"/><path class="rl_hdkaxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:infinitode" /></template>
<style>
.e73y3rbuu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.75 34.237l7.336-6.174l-2.647-8.033l-5.339-.092");
}

.mp6tqxbcn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 29.223l9.1-9.285l3.575 1.067l1.068 5.525l-4.364 2.368l-2.693-2.693l-3.018 2.833l6.082 5.199l9.75-4.921l-1.346-11.7l-10.493-6.918L24 18.777l-9.1 9.286l-3.575-1.068l-1.068-5.525l4.364-2.368l2.693 2.693l3.018-2.833l-6.082-5.2l-9.75 4.922l1.346 11.7l10.493 6.918z");
}

.rl_hdkaxz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.154 17.616l-10.679-1.3L24 24l-7.475 7.684l-10.679-1.3");
}

.tcpcsm4uz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.25 13.762l-7.336 6.176l2.647 8.032l5.339.093");
}

</style>
