<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohxippw5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:emoji-flags" /></template>
<style>
.ohxippw5a {
  fill: currentColor;
  d: path("M6 20.5V5h7.192l.4 2H19v8h-5.192l-.4-2H7v7.5z");
}

</style>
