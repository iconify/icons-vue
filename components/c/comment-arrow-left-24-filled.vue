<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y137uqbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:comment-arrow-left-24-filled" /></template>
<style>
.y137uqbzh {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0-11a5.5 5.5 0 0 1 0 11m3-5a.5.5 0 0 0 0-1h-4.793l1.647-1.646a.5.5 0 0 0-.708-.708l-2.5 2.5a.5.5 0 0 0 0 .708l2.5 2.5a.5.5 0 0 0 .708-.708L15.707 7zm-3 6a6.48 6.48 0 0 0 4.5-1.81v3.56A3.25 3.25 0 0 1 18.75 18H13l-5 3.75c-.824.618-2 .03-2-1V18h-.75A3.25 3.25 0 0 1 2 14.75v-8.5A3.25 3.25 0 0 1 5.25 3h6.772A6.5 6.5 0 0 0 17.5 13");
}

</style>
