<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="v1h9kshdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:app-store-logo-light" /></template>
<style>
.v1h9kshdn {
  fill: currentColor;
  d: path("m62.62 195.05l-9.45 16A6 6 0 0 1 42.83 205l9.46-16a6 6 0 1 1 10.33 6.1ZM232 154h-48.94l-31.31-53a6 6 0 1 0-10.33 6.11l61.41 103.93a6 6 0 0 0 10.34-6.1l-23-38.95H232a6 6 0 0 0 0-12Zm-89.53 0H86.88l70.29-118.95A6 6 0 0 0 146.83 29L128 60.82L109.17 29a6 6 0 0 0-10.34 6.1L121 72.62L72.94 154H24a6 6 0 0 0 0 12h118.47a6 6 0 1 0 0-12");
}

</style>
