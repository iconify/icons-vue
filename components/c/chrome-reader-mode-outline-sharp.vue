<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ss65rm3ja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chrome-reader-mode-outline-sharp" /></template>
<style>
.ss65rm3ja {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h7V6H4zm9 0h7V6h-7zm1-8h5V8.5h-5zm0 2.5h5V11h-5zm0 2.5h5v-1.5h-5zM4 6v12z");
}

</style>
