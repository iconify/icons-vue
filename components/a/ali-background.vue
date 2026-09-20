<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="x9nub2bem"/><path clip-rule="evenodd" class="oymo3hhwb"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ali-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.oymo3hhwb {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M20 12a8 8 0 1 1-16 0a8 8 0 0 1 16 0m-7.835-5.67c-.325-.315-.435-.62-.45-.83C8.25 5.71 5.5 8.545 5.5 12.01a6.565 6.565 0 0 0 5.99 6.49a5.5 5.5 0 0 0-1.375-1.31c-.135-.1-.285-.225-.335-.4c-.055-.215.205-.42.345-.5a.94.94 0 0 0 .32-.305c.1-.17.035-.24-.05-.32l-.034-.04a.5.5 0 0 1-.076-.105c-.05-.095-.055-.21.025-.295c.085-.09.26-.115.365-.115c-.235-.015-.31-.2-.31-.29c0-.14.125-.21.25-.275l.062-.04a1 1 0 0 0 .088-.06c.295-.255.25-.515.215-.63a.8.8 0 0 0-.115-.22l-.02-.03l-.008-.011c-.097-.142-.195-.284-.132-.454c.07-.21.375-.355.55-.43c.7-.285 1.51-.82 1.73-1.055c.335-.36-.005-.705-.22-.865c-.23-.165-.255-.425-.255-.55c0-.258.173-.374.322-.473l.003-.002l.135-.1c0-.215-.185-.265-.275-.265c.49-.22.29-.45.22-.5c-.075-.06-.31-.255-.295-.4c.02-.14.2-.25.635-.5c.35-.2.25-.43.15-.52a33 33 0 0 1-1.24-1.11");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.x9nub2bem {
  fill: var(--svg-color--29abe2, #29abe2);
  d: path("M24 0H0v24h24z");
}

</style>
