<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-qcybbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-skip-next" /></template>
<style>
.u-qcybbwx {
  fill: currentColor;
  d: path("m6 18l8.5-6L6 6zM16 6v12h2V6z");
}

</style>
