<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="dny4zfbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:barbell-thin" /></template>
<style>
.dny4zfbuj {
  fill: currentColor;
  d: path("M248 124h-12V88a12 12 0 0 0-12-12h-20V64a12 12 0 0 0-12-12h-24a12 12 0 0 0-12 12v60h-56V64a12 12 0 0 0-12-12H64a12 12 0 0 0-12 12v12H32a12 12 0 0 0-12 12v36H8a4 4 0 0 0 0 8h12v36a12 12 0 0 0 12 12h20v12a12 12 0 0 0 12 12h24a12 12 0 0 0 12-12v-60h56v60a12 12 0 0 0 12 12h24a12 12 0 0 0 12-12v-12h20a12 12 0 0 0 12-12v-36h12a4 4 0 0 0 0-8M32 172a4 4 0 0 1-4-4V88a4 4 0 0 1 4-4h20v88Zm60 20a4 4 0 0 1-4 4H64a4 4 0 0 1-4-4V64a4 4 0 0 1 4-4h24a4 4 0 0 1 4 4Zm104 0a4 4 0 0 1-4 4h-24a4 4 0 0 1-4-4V64a4 4 0 0 1 4-4h24a4 4 0 0 1 4 4Zm32-24a4 4 0 0 1-4 4h-20V84h20a4 4 0 0 1 4 4Z");
}

</style>
