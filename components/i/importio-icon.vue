<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":346};
const content = `<path class="nd9lvvb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:importio-icon" /></template>
<style>
.nd9lvvb1h {
  fill: var(--svg-color--772ce8, #772ce8);
  d: path("m82.269 182.197l82.284 81.872l-82.284 81.858L0 264.053zm91.446-91.023L256 173.047l-82.285 81.857l-82.27-81.874zM82.27 0l82.284 81.873l-82.284 81.856L0 81.857z");
}

</style>
