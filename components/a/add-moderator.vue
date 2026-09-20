<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-ooubcvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:add-moderator" /></template>
<style>
.f-ooubcvr {
  fill: currentColor;
  d: path("M17 22q-2.075 0-3.537-1.463T12 17t1.463-3.537T17 12t3.538 1.463T22 17t-1.463 3.538T17 22m-5 0q-3.475-.875-5.738-3.988T4 11.1V5l8-3l8 3v5.675q-.65-.325-1.463-.5T17 10q-2.9 0-4.95 2.05T10 17q0 1.55.588 2.8t1.487 2.175q-.025 0-.037.013T12 22m4.5-2h1v-2.5H20v-1h-2.5V14h-1v2.5H14v1h2.5z");
}

</style>
