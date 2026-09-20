<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="kx1z__7ld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:glance-horizontal-28-filled" /></template>
<style>
.kx1z__7ld {
  fill: currentColor;
  d: path("M3 5.75A2.75 2.75 0 0 1 5.75 3h6.5A2.75 2.75 0 0 1 15 5.75v4.5A2.75 2.75 0 0 1 12.25 13h-6.5A2.75 2.75 0 0 1 3 10.25zM20.75 3A2.75 2.75 0 0 0 18 5.75v4.5A2.75 2.75 0 0 0 20.75 13h1.5A2.75 2.75 0 0 0 25 10.25v-4.5A2.75 2.75 0 0 0 22.25 3zm-15 12A2.75 2.75 0 0 0 3 17.75v4.5A2.75 2.75 0 0 0 5.75 25h1.5A2.75 2.75 0 0 0 10 22.25v-4.5A2.75 2.75 0 0 0 7.25 15zm10 0A2.75 2.75 0 0 0 13 17.75v4.5A2.75 2.75 0 0 0 15.75 25h6.5A2.75 2.75 0 0 0 25 22.25v-4.5A2.75 2.75 0 0 0 22.25 15z");
}

</style>
