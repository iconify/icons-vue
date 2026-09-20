<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="pp1jvfbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:agents-12-filled" /></template>
<style>
.pp1jvfbua {
  fill: currentColor;
  d: path("M7.93 2a1.5 1.5 0 0 1 1.29.733l1.638 2.756c.187.315.187.707 0 1.022l-1.783 3a1 1 0 0 1-.86.489h-1.97c.179-.239.318-.512.403-.812l1.586-5.55a.5.5 0 0 0-.96-.276l-1.587 5.55a1.5 1.5 0 0 1-1.303 1.081L4.226 10h-.157c-.529 0-1.02-.279-1.29-.733L1.142 6.51a1 1 0 0 1 0-1.022l1.783-3A1 1 0 0 1 3.785 2h1.972c-.18.24-.32.512-.406.813l-1.585 5.55a.5.5 0 0 0 .96.275l1.585-5.55A1.5 1.5 0 0 1 7.755 2z");
}

</style>
