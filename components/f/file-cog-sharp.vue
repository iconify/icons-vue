<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vaz6l1paq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-cog-sharp" /></template>
<style>
.vaz6l1paq {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 11L20 8L14 2L4 2L4 22L9 22M14 2L14 8L20 8M18.6667 18C18.6667 19.4728 17.4728 20.6667 16 20.6667C14.5272 20.6667 13.3333 19.4728 13.3333 18C13.3333 16.5272 14.5272 15.3333 16 15.3333C17.4728 15.3333 18.6667 16.5272 18.6667 18ZM18.99 18L21 18M18.1142 20.1142L19.5355 21.5355M16 20.99L16 23M13.8858 20.1142L12.4645 21.5355M13.01 18L11 18M13.8858 15.8858L12.4645 14.4645M16 15.01L16 13M18.1142 15.8858L19.5355 14.4645");
}

</style>
