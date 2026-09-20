<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz6hsxgwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:box-search-24-filled" /></template>
<style>
.iz6hsxgwy {
  fill: currentColor;
  d: path("M13.409 2.512a3.75 3.75 0 0 0-2.818 0l-2.19.888l9.592 3.73l3.374-1.303a1.8 1.8 0 0 0-.46-.275zM22 7.19l-9.25 3.574v10.923q.336-.068.659-.199l7.498-3.04A1.75 1.75 0 0 0 22 16.826zm-10.75 3.574v10.01L9.425 18.95A5.5 5.5 0 0 0 2 11.6V7.19zM2.633 5.827L12 9.446l3.917-1.514l-9.543-3.71l-3.281 1.33q-.256.104-.46.275M4.5 21a4.5 4.5 0 0 0 2.607-.832L9.72 22.78a.75.75 0 1 0 1.06-1.06l-2.612-2.613A4.5 4.5 0 1 0 4.5 21m0-1.5a3 3 0 1 1 0-6a3 3 0 0 1 0 6");
}

</style>
