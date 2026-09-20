<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b8bjh6b3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-up-left-48-filled" /></template>
<style>
.b8bjh6b3u {
  fill: currentColor;
  d: path("M35 40.5a1.5 1.5 0 0 0 3 0v-18a7.5 7.5 0 0 0-7.5-7.5H13.121l6.44-6.44a1.5 1.5 0 0 0-2.122-2.12l-9 9a1.5 1.5 0 0 0 0 2.12l9 9a1.5 1.5 0 0 0 2.122-2.12L13.12 18H30.5a4.5 4.5 0 0 1 4.5 4.5z");
}

</style>
