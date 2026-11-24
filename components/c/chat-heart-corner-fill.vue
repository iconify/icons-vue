<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqsx3ks9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-heart-corner-fill" /></template>
<style>
.uqsx3ks9k {
  fill: currentColor;
  d: path("M11 10a.997.997 0 0 0-1 1v6a1 1 0 0 1-1 1H8c-.468 0-.98.395-1.293.707l-2 2a1.36 1.36 0 0 1-1.186.382C2.572 20.928 2 19.898 2 19V5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v4a1 1 0 0 1-1 1Zm6 4.398a3.7 3.7 0 0 1 2.375-.898c1.468 0 2.625.986 2.625 2.5c-.001 1.964-2.294 3.6-3.871 4.52q-.335.198-.682.374a1 1 0 0 1-.894 0A15.4 15.4 0 0 1 14.4 19.55c-1.103-.828-2.399-2.058-2.4-3.55c0-1.514 1.157-2.5 2.625-2.5c.869 0 1.718.335 2.375.898");
}

</style>
