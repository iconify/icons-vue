<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ychg8xbku"/><path class="kcwg0op2l"/><path class="rhbnyb5vv"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gdcc-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kcwg0op2l {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.158 14.105c-.299 1.558-1.41 4.21-3.368 4.21c-2.106 0-2.948-4.404-2.948-6.315c0-3.369 1.474-6.316 2.948-6.316c1.591 0 3.035 2.391 3.368 3.79c-.564-2.468-1.777-4.211-3.368-4.211C5.697 5.263 4 8.277 4 12c0 3.722 1.697 6.736 3.79 6.736c1.68 0 2.871-1.94 3.368-4.631");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rhbnyb5vv {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.008 14.106c-.311 1.369-.91 2.737-1.84 2.737c-1.065 0-1.84-1.036-2.471-1.878l-.013-.017c.522 1.516 1.44 2.527 2.484 2.527c1.226 0 2.274-1.39 2.72-3.369h-.884zm.775-4.631c-.492-1.752-1.478-2.948-2.615-2.948S6.177 7.723 5.684 9.475l.16-.266c.581-.989 1.209-2.05 2.324-2.05c.91 0 1.466 1.103 1.777 2.316h.842zM7.79 10.738h2.105v-.842H7.789c-.673 0-.842.56-.842.842v2.105c0 .674.56.842.842.842h1.264c.673 0 .842-.56.842-.842V11.58H8.21v.842h.843v.421H7.789zm6.736 2.105v-2.105h1.263v.42h.843v-.42c0-.421-.224-.842-.843-.842h-1.263c-.673 0-.842.56-.842.842v2.105c0 .674.56.842.842.842h1.263c.674 0 .843-.56.843-.842v-.421h-.843v.421zm3.369 0v-2.105h1.263v.42H20v-.42c0-.421-.223-.842-.842-.842h-1.263c-.674 0-.842.56-.842.842v2.105c0 .674.56.842.842.842h1.263c.674 0 .842-.56.842-.842v-.421h-.842v.421zm-7.58-2.105v-.842h2.106c.674 0 .842.56.842.842v2.105c0 .674-.56.842-.842.842h-2.105V11.16h.842v1.684h1.263v-2.105z");
}

.ychg8xbku {
  fill: var(--svg-color--ce1db4, #ce1db4);
  d: path("M24 0H0v24h24z");
}

</style>
