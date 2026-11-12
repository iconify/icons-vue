<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":246};
const content = `<path class="lmrdhabwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:deepgram-icon" /></template>
<style>
.lmrdhabwc {
  fill: var(--svg-color--e042ff, #e042ff);
  d: path("M0 222.194c39.796-8.292 47.753-24.206 47.753-67.986v-63.01c0-43.77-7.957-59.693-47.753-67.985L7.298 0C37.81 6.63 52.071 6.63 66.324 6.63c11.606 0 23.213-1.328 34.485-2.656s22.553-2.656 34.484-2.656C203.938 1.318 256 52.386 256 122.694c0 70.307-52.062 121.375-120.707 121.375c-11.94 0-23.212-1.328-34.484-2.656s-22.879-2.655-34.485-2.655c-14.262 0-28.524 0-59.026 6.629L0 222.174zm135.303-4.308c46.101 0 72.953-35.488 72.953-95.173c0-59.684-26.862-95.172-72.953-95.172c-28.514 0-46.425 15.59-46.425 63.668v63.009c0 48.088 17.91 63.668 46.425 63.668");
}

</style>
