<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obc54jjkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:flash-auto-outline" /></template>
<style>
.obc54jjkr {
  fill: currentColor;
  d: path("m7 15.6l3.2-4.6H7.35l2-7H4v8h3zM5 22v-8H2V2h10l-2 7h4zm2-10H4zm7.625-1L18 2h1.6l3.425 9h-1.55l-.8-2.3h-3.7l-.8 2.3zm2.8-3.6h2.75L18.85 3.65h-.05z");
}

</style>
