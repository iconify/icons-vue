<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-omdubcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:door-sensor-outline-rounded" /></template>
<style>
.s-omdubcg {
  fill: currentColor;
  d: path("M9 15V5v14zm-1 .5h1v2.885q0 .269.173.442t.443.173h4.769q.269 0 .442-.173t.173-.443V5.616q0-.27-.173-.443T14.385 5h-4.77q-.269 0-.442.173T9 5.616V14.5H8V5.616q0-.667.475-1.141T9.615 4h4.77q.666 0 1.14.475T16 5.615v12.77q0 .666-.475 1.14t-1.14.475h-4.77q-.666 0-1.14-.475T8 18.386zm4-5.73q.31 0 .54-.23t.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23m7.5-1.27q-.213 0-.357-.144T19 8V4q0-.213.144-.356t.357-.144t.356.144T20 4v4q0 .213-.144.356t-.357.144m-13.614 7q-.213 0-.357-.144t-.144-.357t.144-.356t.356-.143h6.385q.213 0 .356.144t.144.357t-.144.356t-.356.143z");
}

</style>
