<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltop3pb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dual-screen-group-24-regular" /></template>
<style>
.ltop3pb7t {
  fill: currentColor;
  d: path("M12.755 4.002v.002h7.498c.966 0 1.75.784 1.75 1.75V18.25a1.75 1.75 0 0 1-1.75 1.75h-8.998v-.003H3.758a1.75 1.75 0 0 1-1.75-1.75V5.752c0-.967.783-1.75 1.75-1.75zm7.498 1.502h-7.498V18.5h7.498a.25.25 0 0 0 .25-.25V5.754a.25.25 0 0 0-.25-.25m-8.998-.002H3.758a.25.25 0 0 0-.25.25v12.495c0 .138.112.25.25.25h7.497z");
}

</style>
