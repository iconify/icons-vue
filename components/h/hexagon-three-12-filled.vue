<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="g3hthybnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:hexagon-three-12-filled" /></template>
<style>
.g3hthybnf {
  fill: currentColor;
  d: path("M2.715 1.998A1 1 0 0 1 3.58 1.5h1.164a1 1 0 0 1 .865.498l.58 1a1 1 0 0 1 0 1.004l-.58 1a1 1 0 0 1-.865.498H3.58a1 1 0 0 1-.865-.498l-.58-1a1 1 0 0 1 0-1.004zm4.33 2.5A1 1 0 0 1 7.91 4h1.164a1 1 0 0 1 .865.498l.58 1a1 1 0 0 1 0 1.004l-.58 1A1 1 0 0 1 9.074 8H7.91a1 1 0 0 1-.865-.498l-.58-1a1 1 0 0 1 0-1.004zM3.58 6.5a1 1 0 0 0-.865.498l-.58 1a1 1 0 0 0 0 1.004l.58 1a1 1 0 0 0 .865.498h1.164a1 1 0 0 0 .865-.498l.58-1a1 1 0 0 0 0-1.004l-.58-1a1 1 0 0 0-.865-.498z");
}

</style>
