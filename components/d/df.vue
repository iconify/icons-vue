<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xe0coubdn"/><path class="tyavo3n9o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:df" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.tyavo3n9o {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.3 3h5.4a9 9 0 1 1 0 18H6.9V10.2h1.8v9h3a7.2 7.2 0 0 0 0-14.4H6.3z");
}

.xe0coubdn {
  fill: var(--svg-color--ff9601, #ff9601);
  d: path("M3.3 6.6h7.8a5.4 5.4 0 0 1 0 10.8h-.6v-1.986h.258c2.179 0 3.943-1.584 3.943-3.51c0-1.92-1.764-3.504-3.943-3.504H5.1v10.2H3.3z");
}

</style>
