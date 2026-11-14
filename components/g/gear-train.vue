<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n0u90qb9o"/><path class="xsl8hw7at"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gear-train" /></template>
<style>
.n0u90qb9o {
  d: path("m6.513 8.578l.105-1.286h1.264l.105 1.286l1.162.482l.983-.836l.894.894l-.836.983l.482 1.162l1.286.105v1.264l-1.286.105l-.482 1.162l.836.983l-.894.894l-.983-.836l-1.162.482l-.105 1.286H6.618l-.105-1.286l-1.162-.482l-.983.836l-.894-.894l.836-.983l-.482-1.162l-1.286-.105v-1.264l1.286-.105l.482-1.162l-.836-.983l.894-.894l.983.836Zm10.4.541l.129-1.056h1.416l.129 1.056l1.239.716l.979-.417l.709 1.227l-.851.639v1.432l.851.639l-.709 1.227l-.979-.417l-1.239.716l-.129 1.056h-1.416l-.129-1.056l-1.239-.716l-.979.417l-.709-1.227l.851-.639v-1.432l-.851-.639l.709-1.227l.979.417Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xsl8hw7at {
  d: path("M5.75 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm11 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

</style>
