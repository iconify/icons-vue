<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kca7tja6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hd-outline-sharp" /></template>
<style>
.kca7tja6x {
  fill: currentColor;
  d: path("M6.616 14.692H7.5v-2h2.616v2H11V9.308h-.885v2.5H7.5v-2.5h-.885zm6.384 0h3.789l.595-.615V9.904l-.596-.596H13zm.885-.884v-3.616H16.5v3.616zM3 19V5h18v14zm1-1h16V6H4zm0 0V6z");
}

</style>
