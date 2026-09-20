<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti6naibhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:enhanced-encryption-sharp" /></template>
<style>
.ti6naibhj {
  fill: currentColor;
  d: path("M11.5 15.5v3h1v-3h3v-1h-3v-3h-1v3h-3v1zM5 21V9h3V7q0-1.671 1.165-2.835Q10.329 3 12 3t2.836 1.165T16 7v2h3v12zM9 9h6V7q0-1.25-.875-2.125T12 4t-2.125.875T9 7z");
}

</style>
