<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eau1vob4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:border-top-bottom-24-filled" /></template>
<style>
.eau1vob4t {
  fill: currentColor;
  d: path("M4 7a1 1 0 0 1-1-1a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3a1 1 0 1 1-2 0a1 1 0 0 0-1-1H6a1 1 0 0 0-1 1a1 1 0 0 1-1 1m1 4a1 1 0 1 0-2 0v2a1 1 0 1 0 2 0zm14 0a1 1 0 1 1 2 0v2a1 1 0 1 1-2 0zM3 18a1 1 0 1 1 2 0a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1a1 1 0 1 1 2 0a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3");
}

</style>
