<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="hikiw_gwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:diamond-link-28-regular" /></template>
<style>
.hikiw_gwd {
  fill: currentColor;
  d: path("M10.872 7.54a9.56 9.56 0 0 1 6.781 2.807a9.585 9.585 0 0 1 0 13.555l-1.002 1a3.75 3.75 0 0 1-5.301 0l-8.252-8.251a3.75 3.75 0 0 1 0-5.303l1-1a9.6 9.6 0 0 1 2.725-1.912c-.144.61-.234 1.232-.268 1.856a8 8 0 0 0-1.396 1.116l-1 1a2.25 2.25 0 0 0 0 3.182l8.251 8.251a2.25 2.25 0 0 0 3.18.001l1.003-1.002a8.084 8.084 0 0 0-6.32-13.776a7 7 0 0 1 .6-1.524m.477-4.443a3.75 3.75 0 0 1 5.302.001l8.251 8.251a3.75 3.75 0 0 1 .002 5.303l-1.003 1.004a9.6 9.6 0 0 1-2.727 1.911c.144-.611.234-1.233.268-1.857a8 8 0 0 0 1.399-1.115l1.002-1.004a2.25 2.25 0 0 0-.001-3.18L15.59 4.159a2.25 2.25 0 0 0-3.182 0L11.407 5.16a8.086 8.086 0 0 0 0 11.434a8.07 8.07 0 0 0 6.316 2.343a7 7 0 0 1-.598 1.524a9.55 9.55 0 0 1-6.778-2.806c-3.743-3.743-3.743-9.813 0-13.556z");
}

</style>
