<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p64rd2dil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:leaderboard-outline-rounded" /></template>
<style>
.p64rd2dil {
  fill: currentColor;
  d: path("M4 19h4.673v-8H4zm5.673 0h4.654V5H9.673zm5.654 0H20v-6h-4.673zM3 18.384v-6.768q0-.667.475-1.141T4.615 10h4.058V5.616q0-.667.475-1.141T10.288 4h3.424q.666 0 1.14.475t.475 1.14V12h4.058q.666 0 1.14.475t.475 1.14v4.77q0 .666-.475 1.14t-1.14.475H4.615q-.666 0-1.14-.475T3 18.386");
}

</style>
