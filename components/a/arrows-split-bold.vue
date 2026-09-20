<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="uw5onu1gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrows-split-bold" /></template>
<style>
.uw5onu1gr {
  fill: currentColor;
  d: path("m232.49 192.49l-32 32a12 12 0 0 1-17 0l-32-32a12 12 0 0 1 17-17L180 187v-46l-52-52l-52 52v46l11.51-11.52a12 12 0 0 1 17 17l-32 32a12 12 0 0 1-17 0l-32-32a12 12 0 1 1 17-17L52 187v-51a12 12 0 0 1 3.51-8.49L116 67V24a12 12 0 0 1 24 0v43l60.49 60.48A12 12 0 0 1 204 136v51l11.51-11.52a12 12 0 0 1 17 17Z");
}

</style>
