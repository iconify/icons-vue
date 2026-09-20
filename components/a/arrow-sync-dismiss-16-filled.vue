<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rm_v1bb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-sync-dismiss-16-filled" /></template>
<style>
.rm_v1bb1p {
  fill: currentColor;
  d: path("M11.075 3.412a.5.5 0 0 1 .703-.073a6 6 0 0 1-3.574 10.657l.65.65a.5.5 0 0 1-.708.708l-1.5-1.5a.5.5 0 0 1 0-.707l.267-.268c.35.078.714.121 1.087.121c2.666 0 5-2.271 5-5a4.99 4.99 0 0 0-1.852-3.885a.5.5 0 0 1-.073-.703M7.146.647a.5.5 0 0 1 .708 0l1.5 1.5a.5.5 0 0 1 0 .707l-.267.265A5 5 0 0 0 8 3C5.321 3 3 5.254 3 8a4.99 4.99 0 0 0 1.852 3.885a.5.5 0 1 1-.63.776A6 6 0 0 1 7.796 2.003l-.65-.65a.5.5 0 0 1 0-.706M8 4a4 4 0 1 1 0 8a4 4 0 0 1 0-8m1.353 2.647a.5.5 0 0 0-.707 0l-.647.645l-.645-.645a.5.5 0 0 0-.708.707l.646.645l-.646.648a.5.5 0 0 0 .708.707l.645-.648l.647.648a.5.5 0 0 0 .708-.707l-.648-.648l.647-.645a.5.5 0 0 0 0-.707");
}

</style>
