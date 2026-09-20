<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="gm_buhhvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:keyhole-fill" /></template>
<style>
.gm_buhhvf {
  fill: currentColor;
  d: path("M128 24a104 104 0 1 0 104 104A104.11 104.11 0 0 0 128 24m29.52 146.39a4 4 0 0 1-3.66 5.61h-51.72a4 4 0 0 1-3.66-5.61L112 139.72a32 32 0 1 1 32 0Z");
}

</style>
