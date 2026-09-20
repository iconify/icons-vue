<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="srkoj1btu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-mail-20-filled" /></template>
<style>
.srkoj1btu {
  fill: currentColor;
  d: path("M2 5.5A2.5 2.5 0 0 1 4.5 3h2.482c.464 0 .91.184 1.238.513l1.28 1.28l-2.06 2.06A.5.5 0 0 1 7.085 7H2zM2 8v6.5A2.5 2.5 0 0 0 4.5 17h4.55a2.5 2.5 0 0 1-.05-.5v-4a2.5 2.5 0 0 1 2.5-2.5h6q.257 0 .5.05V7.5A2.5 2.5 0 0 0 15.5 5h-4.793l-2.56 2.56A1.5 1.5 0 0 1 7.085 8zm8.013 4.304l4.497 2.623L19 12.509V12.5a1.5 1.5 0 0 0-1.5-1.5h-6a1.5 1.5 0 0 0-1.487 1.304M19 13.644l-4.263 2.296a.5.5 0 0 1-.489-.008L10 13.454V16.5a1.5 1.5 0 0 0 1.5 1.5h6a1.5 1.5 0 0 0 1.5-1.5z");
}

</style>
