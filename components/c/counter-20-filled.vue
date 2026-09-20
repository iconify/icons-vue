<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y9mp4_bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:counter-20-filled" /></template>
<style>
.y9mp4_bvi {
  fill: currentColor;
  d: path("M6 7a1 1 0 0 1 1 1v3a1 1 0 1 1-2 0V8a1 1 0 0 1 1-1m3.5 9H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h5.5zM6 6a2 2 0 0 0-2 2v3a2 2 0 1 0 4 0V8a2 2 0 0 0-2-2m6 0a2 2 0 1 0 4 0V3a2 2 0 0 1 2 2v9a2 2 0 0 1-2 2h-1v-5.5a.5.5 0 0 0-.916-.277l-.009.011q-.015.021-.052.065a2.2 2.2 0 0 1-1.145.716a.501.501 0 0 0 .243.97a3.1 3.1 0 0 0 .879-.369V16h-3.5V3H12zm3 0a1 1 0 1 1-2 0V3h2z");
}

</style>
