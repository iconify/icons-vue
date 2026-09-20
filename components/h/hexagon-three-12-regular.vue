<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="tyy5h1-9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:hexagon-three-12-regular" /></template>
<style>
.tyy5h1-9z {
  fill: currentColor;
  d: path("M3.58 1.5a1 1 0 0 0-.865.498l-.58 1a1 1 0 0 0 0 1.004l.58 1a1 1 0 0 0 .865.498h1.164a1 1 0 0 0 .865-.498l.58-1a1 1 0 0 0 0-1.004l-.58-1a1 1 0 0 0-.865-.498zm0 1h1.164l.58 1l-.58 1H3.58L3 3.5zm3.465 1.998A1 1 0 0 1 7.91 4h1.164a1 1 0 0 1 .865.498l.58 1a1 1 0 0 1 0 1.004l-.58 1A1 1 0 0 1 9.074 8H7.91a1 1 0 0 1-.865-.498l-.58-1a1 1 0 0 1 0-1.004zM9.074 5H7.91l-.58 1l.58 1h1.164l.58-1zM2.715 6.998A1 1 0 0 1 3.58 6.5h1.164a1 1 0 0 1 .865.498l.58 1a1 1 0 0 1 0 1.004l-.58 1a1 1 0 0 1-.865.498H3.58a1 1 0 0 1-.865-.498l-.58-1a1 1 0 0 1 0-1.004zm2.029.502H3.58L3 8.5l.58 1h1.164l.58-1z");
}

</style>
