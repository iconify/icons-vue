<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ncmlbj9lr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-closed-key-16-filled" /></template>
<style>
.ncmlbj9lr {
  fill: currentColor;
  d: path("M13 7a3 3 0 1 1-1 5.83v.67a.5.5 0 0 1-.5.5H11v.5a.5.5 0 0 1-.5.5H10v.5a.5.5 0 0 1-.5.5h-2a.5.5 0 0 1-.5-.5v-1.086a1 1 0 0 1 .293-.707l2.836-2.836A3 3 0 0 1 13 7M7 1a3 3 0 0 1 3 3v2c.46 0 .882.156 1.22.417a4 4 0 0 0-2.183 4.132L6.586 13A2 2 0 0 0 6 14.414V15H4a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2V4a3 3 0 0 1 3-3m0 8.5a1 1 0 1 0 0 2a1 1 0 0 0 0-2m6.75-1a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5M7 2a2 2 0 0 0-2 2v2h4V4a2 2 0 0 0-2-2");
}

</style>
