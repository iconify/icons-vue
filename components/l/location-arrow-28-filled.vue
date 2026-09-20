<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="gf9tqvbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:location-arrow-28-filled" /></template>
<style>
.gf9tqvbwk {
  fill: currentColor;
  d: path("M23.959 2.104c1.213-.467 2.405.725 1.938 1.938L17.821 25.04c-.522 1.36-2.48 1.251-2.85-.157l-2.358-8.96a.75.75 0 0 0-.535-.534l-8.96-2.358c-1.408-.37-1.515-2.328-.156-2.85z");
}

</style>
