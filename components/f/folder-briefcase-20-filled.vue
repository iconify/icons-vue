<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g-v5f6b4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-briefcase-20-filled" /></template>
<style>
.g-v5f6b4s {
  fill: currentColor;
  d: path("M2 5.5A2.5 2.5 0 0 1 4.5 3h2.482c.464 0 .91.184 1.238.513l1.28 1.28l-2.06 2.06A.5.5 0 0 1 7.085 7H2zM2 8v6.5A2.5 2.5 0 0 0 4.5 17H9v-3.5a2.5 2.5 0 0 1 2.042-2.458A2.5 2.5 0 0 1 13.5 9h2a2.5 2.5 0 0 1 2.458 2.042l.042.008V7.5A2.5 2.5 0 0 0 15.5 5h-4.793l-2.56 2.56A1.5 1.5 0 0 1 7.085 8zm10 3.5v.5h-.5a1.5 1.5 0 0 0-1.5 1.5v4a1.5 1.5 0 0 0 1.5 1.5h6a1.5 1.5 0 0 0 1.5-1.5v-4a1.5 1.5 0 0 0-1.5-1.5H17v-.5a1.5 1.5 0 0 0-1.5-1.5h-2a1.5 1.5 0 0 0-1.5 1.5m1.5-.5h2a.5.5 0 0 1 .5.5v.5h-3v-.5a.5.5 0 0 1 .5-.5");
}

</style>
