<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="e4v06ma2o"/><path clip-rule="evenodd" class="b0heapb3w"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:daimo-background" /></template>
<style>
.b0heapb3w {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12.433 19.747a.505.505 0 0 1-.874 0L4.069 6.789a.514.514 0 0 1 .183-.698A15.3 15.3 0 0 1 12 4c2.821 0 5.468.761 7.747 2.091a.51.51 0 0 1 .184.699zm-.235-1.632c.04-.054.084-.13.144-.236l5.527-9.55c-.24.026-.483.02-.726-.005c-.81-.083-1.734-.405-2.635-.718h-.002l-.292-.102c-1.027-.355-2.04-.68-3-.74c-.778-.05-1.497.076-2.143.498a.24.24 0 0 0-.094.27zm-1.777-2.361L7.858 7.333a.51.51 0 0 1 .148-.532c.995-.889 2.137-1.127 3.27-1.055c1.114.07 2.25.442 3.266.793l.275.095c.935.325 1.743.605 2.43.676c.365.037.654.01.884-.08l.076-.03c.163-.06.33-.123.467-.269a.3.3 0 0 0 .027-.097a.25.25 0 0 0-.046-.154c-.036-.05-.099-.082-.224-.145A14.3 14.3 0 0 0 12 5.02c-2.31 0-4.494.546-6.431 1.516c-.125.062-.188.094-.224.144a.25.25 0 0 0-.046.154c.002.062.038.124.11.249z");
}

.e4v06ma2o {
  fill: var(--svg-color--71be6c, #71be6c);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
