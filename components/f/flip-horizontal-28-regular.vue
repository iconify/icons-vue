<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="d8bjtn7sr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flip-horizontal-28-regular" /></template>
<style>
.d8bjtn7sr {
  fill: currentColor;
  d: path("M25.882 23.654a.75.75 0 0 1-.632.346h-9.5a.75.75 0 0 1-.75-.75V2.75a.75.75 0 0 1 1.43-.315l9.5 20.5a.75.75 0 0 1-.048.719M16.5 6.152V22.5h7.576zM2.75 24a.75.75 0 0 1-.68-1.065l9.5-20.5A.75.75 0 0 1 13 2.75v20.5a.75.75 0 0 1-.75.75z");
}

</style>
