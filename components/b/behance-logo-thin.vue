<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kwb5zbcdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:behance-logo-thin" /></template>
<style>
.kwb5zbcdo {
  fill: currentColor;
  d: path("M108.16 122.74A34 34 0 0 0 90 60H32a4 4 0 0 0-4 4v128a4 4 0 0 0 4 4h62a38 38 0 0 0 14.16-73.26M36 68h54a26 26 0 0 1 0 52H36Zm58 120H36v-60h58a30 30 0 0 1 0 60m70-108a4 4 0 0 1 4-4h64a4 4 0 0 1 0 8h-64a4 4 0 0 1-4-4m36 28a44 44 0 1 0 35.2 70.41a4 4 0 0 0-6.4-4.81a36 36 0 0 1-64.58-17.6H240a4 4 0 0 0 4-4a44.05 44.05 0 0 0-44-44m-35.78 40a36 36 0 0 1 71.56 0Z");
}

</style>
