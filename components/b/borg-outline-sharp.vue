<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fonng8qxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:borg-outline-sharp" /></template>
<style>
.fonng8qxd {
  fill: currentColor;
  d: path("M3 17.125V6.875L12 1.7l9 5.175v10.25L12 22.3zM8 16v-3H5v2.95l6 3.475V16zm0-8h3V4.575L5 8.05V11h3zm2 6h4v-4h-4zm6 2h-3v3.425l6-3.475V13h-3zm0-8v3h3V8.05l-6-3.475V8z");
}

</style>
