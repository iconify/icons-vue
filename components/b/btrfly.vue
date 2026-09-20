<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="voezwwbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:btrfly" /></template>
<style>
.voezwwbhs {
  fill: var(--svg-color--fff, #fff);
  d: path("m11.745 10.175l.275 1.075l.235-1.075L18.17 5.75H21l-.77 3.905l-2.73 2.085v.51h.67l.515 2.35l-2.83 3.65H15.6l-1.8-2.6l-1.03 1.6h-.255l-.26-.5h-.505l-.26.5h-.255l-1.03-1.6l-1.8 2.6H8.15L5.32 14.6l.515-2.35H6.5v-.51L3.77 9.655L3 5.75h2.83z");
}

</style>
