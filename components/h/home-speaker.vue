<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo6snzkcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:home-speaker" /></template>
<style>
.mo6snzkcz {
  fill: currentColor;
  d: path("m7.027 12.404l.737-5.748q.03-.217.154-.391t.336-.255l6.727-2.766q.373-.161.711.043t.389.61l.96 8.507zM9.767 20Q8.25 20 7.3 18.82t-.738-2.71l.344-2.706H17.15l.3 2.794q.162 1.511-.763 2.657T14.25 20z");
}

</style>
