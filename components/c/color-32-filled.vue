<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x_a-bqbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:color-32-filled" /></template>
<style>
.x_a-bqbsn {
  fill: currentColor;
  d: path("M16 2c7.732 0 14 6.268 14 14c0 5.302-2.948 9.914-7.288 12.29c-2.076 1.135-4.252.887-5.88-.278c-1.606-1.15-2.625-3.146-2.589-5.428c.021-1.34.008-2.446-.237-3.344c-.228-.835-.641-1.44-1.453-1.845c-.74-.37-1.346-.397-1.896-.28c-.592.126-1.16.425-1.815.806c-.597.347-1.348.82-2.116 1.044c-.858.25-1.793.218-2.736-.404c-1.749-1.157-2.071-3.374-1.768-5.056C3.399 6.964 9.119 2 16 2m4.5 18.75a1.75 1.75 0 1 0 0 3.5a1.75 1.75 0 0 0 0-3.5m4-3.5a1.75 1.75 0 1 0 0 3.5a1.75 1.75 0 0 0 0-3.5m-1-5.5a1.75 1.75 0 1 0 0 3.5a1.75 1.75 0 0 0 0-3.5m-3-4.5a1.75 1.75 0 1 0 0 3.5a1.75 1.75 0 0 0 0-3.5m-5-1.5a1.75 1.75 0 1 0 0 3.5a1.75 1.75 0 0 0 0-3.5");
}

</style>
