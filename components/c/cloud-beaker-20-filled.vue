<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gg_6lqbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cloud-beaker-20-filled" /></template>
<style>
.gg_6lqbvz {
  fill: currentColor;
  d: path("M14.617 8c-.318-2.211-1.9-4-4.617-4c-2.817 0-4.413 1.908-4.647 4.246h-.07C3.468 8.246 2 9.758 2 11.623S3.47 15 5.282 15h6.5l1.104-2.13a1 1 0 0 0 .112-.46v-1.496A1.5 1.5 0 0 1 13.5 8zm2.379 4.405a2 2 0 0 0 .224.92l.35.675h-4.143l.347-.67a2 2 0 0 0 .224-.92V10H13.5a.5.5 0 0 1 0-1h4a.5.5 0 0 1 0 1h-.504zM12.909 15l-.798 1.54A1 1 0 0 0 13 18h4.998a1 1 0 0 0 .888-1.46L18.087 15z");
}

</style>
