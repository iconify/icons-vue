<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tst0wnb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:game-controller-button-b-20-filled" /></template>
<style>
.tst0wnb9n {
  fill: currentColor;
  d: path("M10 2a8 8 0 1 1 0 16a8 8 0 0 1 0-16M8.5 6a.5.5 0 0 0-.5.5v7a.5.5 0 0 0 .5.5h2.25a2.25 2.25 0 0 0 1.125-4.197A2.25 2.25 0 0 0 10.25 6zm2.25 4.5a1.25 1.25 0 1 1 0 2.5H9v-2.5zm-.5-3.5a1.25 1.25 0 1 1 0 2.5H9V7z");
}

</style>
