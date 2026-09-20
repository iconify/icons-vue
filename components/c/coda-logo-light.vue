<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ea5hy0bwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:coda-logo-light" /></template>
<style>
.ea5hy0bwc {
  fill: currentColor;
  d: path("M176 86a41.8 41.8 0 0 1 22.61 6.41A10 10 0 0 0 214 84V48a14 14 0 0 0-14-14H56a14 14 0 0 0-14 14v160a14 14 0 0 0 14 14h144a14 14 0 0 0 14-14v-36a10 10 0 0 0-15.36-8.43c-7.63 4.89-14.11 6.76-22.4 6.42H176a42 42 0 0 1 0-84Zm-54 42a54.06 54.06 0 0 0 53.88 54a46.36 46.36 0 0 0 26.12-6.43V208a2 2 0 0 1-2 2H56a2 2 0 0 1-2-2V48a2 2 0 0 1 2-2h144a2 2 0 0 1 2 2v32.48A54.28 54.28 0 0 0 122 128");
}

</style>
