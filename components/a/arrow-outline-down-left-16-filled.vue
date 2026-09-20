<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kx0v973mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-outline-down-left-16-filled" /></template>
<style>
.kx0v973mc {
  fill: currentColor;
  d: path("M11.151 1.44a1.5 1.5 0 0 0-2.121 0L5.004 5.464L3.907 4.368c-.75-.75-2.033-.285-2.13.77l-.772 8.5a1.25 1.25 0 0 0 1.358 1.358l8.499-.773c1.055-.096 1.52-1.379.77-2.128l-1.098-1.099L14.56 6.97a1.5 1.5 0 0 0 0-2.121z");
}

</style>
