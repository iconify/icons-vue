<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1o6sgjcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-letter-spacing-wider-outline" /></template>
<style>
.y1o6sgjcq {
  fill: currentColor;
  d: path("M3 19V5h1v14zm17 0V5h1v14zM7.773 17l3.673-9.923h1.05L16.227 17h-1.071l-1.015-2.839H9.802L8.806 17zm2.362-3.712h3.692l-1.816-5.111h-.061z");
}

</style>
