<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjs4quflb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clapperboard-fill" /></template>
<style>
.sjs4quflb {
  fill: currentColor;
  d: path("m14.65 3.816l-.185-.983l3.368-.632a2 2 0 0 1 2.334 1.598l.194 1.034a2 2 0 0 1-1.597 2.334l-3.367.632Zm-5.334 1l-.185-.983l3.368-.632l.9 4.799H19a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-8c0-.642.205-1.266.586-1.783l-.006-.033l-.379-2.017a2 2 0 0 1 1.598-2.334l3.367-.632L7.879 8h2.034ZM9 12.5v5a1.284 1.284 0 0 0 1.943 1.1l4.143-2.485a1.3 1.3 0 0 0 0-2.23L10.943 11.4A1.284 1.284 0 0 0 9 12.5");
}

</style>
