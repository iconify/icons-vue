<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="habg8rbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desktop-edit-48-filled" /></template>
<style>
.habg8rbzh {
  fill: currentColor;
  d: path("M24.247 15.51a5 5 0 0 0-1.276 2.253l-.84 3.234c-.764 2.952 1.924 5.64 4.876 4.875l3.234-.839a5 5 0 0 0 2.253-1.276L44 12.427V32.75A4.25 4.25 0 0 1 39.75 37H31v3.5h2.75a1.25 1.25 0 1 1 0 2.5h-19.5a1.25 1.25 0 0 1 0-2.5H17V37H8.25A4.25 4.25 0 0 1 4 32.75V9.25A4.25 4.25 0 0 1 8.25 5h26.346zM19.5 40.5h9V37h-9zM39.183 3.19a3.981 3.981 0 1 1 5.63 5.63L31.089 22.33a3 3 0 0 1-1.352.767l-3.234.838c-1.476.382-2.82-.961-2.437-2.437l.838-3.234a3 3 0 0 1 .767-1.352z");
}

</style>
