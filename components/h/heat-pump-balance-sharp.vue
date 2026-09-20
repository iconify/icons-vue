<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yux85pkol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:heat-pump-balance-sharp" /></template>
<style>
.yux85pkol {
  fill: currentColor;
  d: path("M4.5 7.754v9.769h5v-8.77h3v8.77h5v-9.77h3.906l-1.694 1.65l.688.714l2.889-2.863L20.4 4.366l-.688.713l1.675 1.675H16.5v9.769h-3v-8.77h-5v8.77h-3v-8.77zM2 20.6v-8.461h20V20.6z");
}

</style>
