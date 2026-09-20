<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="xedky4_ip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:doctor-28-filled" /></template>
<style>
.xedky4_ip {
  fill: currentColor;
  d: path("M10.75 2.998A1.75 1.75 0 0 0 9 4.748V9H4.75A1.75 1.75 0 0 0 3 10.75v6.5c0 .966.784 1.75 1.75 1.75H9v4.251c0 .967.784 1.75 1.75 1.75h6.5a1.75 1.75 0 0 0 1.75-1.75V19h4.25A1.75 1.75 0 0 0 25 17.25v-6.5A1.75 1.75 0 0 0 23.25 9H19V4.748a1.75 1.75 0 0 0-1.75-1.75z");
}

</style>
