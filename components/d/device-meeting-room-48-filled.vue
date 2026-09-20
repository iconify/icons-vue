<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jgp9acc8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-48-filled" /></template>
<style>
.jgp9acc8u {
  fill: currentColor;
  d: path("M8.97 10.403A5.94 5.94 0 0 1 14.708 6h18.586a5.94 5.94 0 0 1 5.736 4.403l4.756 17.769c1.057 3.95-1.92 7.828-6.009 7.828H10.224c-4.09 0-7.066-3.878-6.01-7.828zM13.25 38a1.25 1.25 0 1 0 0 2.5h21.5a1.25 1.25 0 1 0 0-2.5z");
}

</style>
