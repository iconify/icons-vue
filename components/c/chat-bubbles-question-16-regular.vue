<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bjg4lxbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-bubbles-question-16-regular" /></template>
<style>
.bjg4lxbhq {
  fill: currentColor;
  d: path("M13.82 5.428A5.97 5.97 0 0 1 15 9a6 6 0 0 1-.71 2.825l.692 2.543a.5.5 0 0 1-.64.607l-2.344-.783A5.97 5.97 0 0 1 9 15a5.97 5.97 0 0 1-3.571-1.179a7 7 0 0 0 2.657.094q.445.084.914.085c.984 0 1.9-.285 2.674-.775c.136-.087.276-.085.426-.053l1.673.557l-.5-1.832a.5.5 0 0 1 .05-.384a4.97 4.97 0 0 0 .592-3.427Q14 7.554 14 7a7 7 0 0 0-.18-1.572M7 1a6 6 0 0 1 0 12a5.97 5.97 0 0 1-2.998-.808l-2.344.783a.5.5 0 0 1-.64-.607l.692-2.543A6 6 0 0 1 1 7a6 6 0 0 1 6-6m0 1a5 5 0 0 0-4.323 7.513a.5.5 0 0 1 .05.383l-.5 1.833l1.673-.557c.15-.033.29-.034.426.053A5 5 0 1 0 7 2m0 7a.75.75 0 1 1 0 1.5A.75.75 0 0 1 7 9m0-5.5c.967 0 1.75.784 1.75 1.75c0 .778-.465 1.234-.747 1.559c-.284.327-.503.62-.503 1.191a.5.5 0 0 1-1 0c0-.93.406-1.453.747-1.847c.343-.395.503-.565.503-.903a.75.75 0 0 0-1.5 0a.5.5 0 0 1-1 0c0-.966.784-1.75 1.75-1.75");
}

</style>
