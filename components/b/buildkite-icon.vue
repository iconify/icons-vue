<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":171};
const content = `<path class="rg9h9i29q"/><path class="fwlhz_r_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:buildkite-icon" /></template>
<style>
.fwlhz_r_i {
  fill: var(--svg-color--14cc80, #14cc80);
  d: path("M171.52 0L85.333 41.813v85.334l86.187-41.814zM256 41.813l-84.48 43.52v85.334l84.48-43.52z");
}

.rg9h9i29q {
  fill: var(--svg-color--30f2a2, #30f2a2);
  d: path("m0 0l85.333 41.813v85.334L0 85.333zm171.52 0L256 41.813l-84.48 43.52z");
}

</style>
