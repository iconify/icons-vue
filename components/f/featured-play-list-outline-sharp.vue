<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8c86-bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:featured-play-list-outline-sharp" /></template>
<style>
.r8c86-bpq {
  fill: currentColor;
  d: path("M6 13h9v-2H6zm0-3h9V8H6zM2 20V4h20v16zm2-2h16V6H4zm0 0V6z");
}

</style>
