<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td6j8dboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:cable-car-outline-sharp" /></template>
<style>
.td6j8dboi {
  fill: currentColor;
  d: path("M7.75 19.77V19H4v-1h1V6H4V5h2.998l.618-1.23h8.75L17.002 5H20v1h-1v12h1v1h-3.75v.77zM6 18h12v-5.538H6zm6.793-1.947q.323-.312.323-.78q0-.466-.327-.792t-.793-.327t-.79.327q-.321.326-.321.793t.326.779t.793.313t.79-.313M6 11.462h3.404v-3.77q0-.705-.493-1.198Q8.418 6 7.714 6t-1.21.494T6 7.692zm4.289 0h3.403v-3.77q0-.705-.493-1.198Q12.708 6 12.003 6t-1.209.494t-.504 1.198zm4.307 0H18v-3.77q0-.705-.505-1.198Q16.99 6 16.286 6t-1.197.494t-.493 1.198zm-8.596 1h12z");
}

</style>
