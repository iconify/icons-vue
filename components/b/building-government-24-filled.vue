<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hp-xwe_zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:building-government-24-filled" /></template>
<style>
.hp-xwe_zl {
  fill: currentColor;
  d: path("M15.5 2h-3.75a.75.75 0 0 0-.75.75v3.32A7 7 0 0 0 5 13h-.75A2.25 2.25 0 0 0 2 15.25v6c0 .414.336.75.75.75H10a.25.25 0 0 0 .25-.25v-3a.5.5 0 0 1 .5-.5h2.5a.5.5 0 0 1 .5.5v3c0 .138.112.25.25.25h7.25a.75.75 0 0 0 .75-.75v-6A2.25 2.25 0 0 0 19.75 13H19a7 7 0 0 0-6.5-6.982V5h3a.5.5 0 0 0 .5-.5v-2a.5.5 0 0 0-.5-.5m0 9.75v2a.75.75 0 0 1-1.5 0v-2a.75.75 0 0 1 1.5 0M11.75 11a.75.75 0 0 1 .75.75v2a.75.75 0 0 1-1.5 0v-2a.75.75 0 0 1 .75-.75m-2.25.75v2a.75.75 0 0 1-1.5 0v-2a.75.75 0 0 1 1.5 0M5.75 15.5a.75.75 0 0 1 .75.75v2.5a.75.75 0 0 1-1.5 0v-2.5a.75.75 0 0 1 .75-.75m13.25.75v2.5a.75.75 0 0 1-1.5 0v-2.5a.75.75 0 0 1 1.5 0");
}

</style>
