<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-v-stthy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-copy" /></template>
<style>
.h-v-stthy {
  fill: currentColor;
  d: path("M3.616 19.77q-.667 0-1.141-.475T2 18.154V7.077h1v11.077q0 .269.173.442t.443.173H19v1zm3-3q-.667 0-1.141-.475T5 15.154V4.616q0-.667.475-1.142T6.615 3h4.962l2 2h6.808q.666 0 1.14.475T22 6.615v8.539q0 .666-.475 1.14t-1.14.475z");
}

</style>
