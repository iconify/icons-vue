<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="qvz9fdbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cloud-arrow-down-28-filled" /></template>
<style>
.qvz9fdbwf {
  fill: currentColor;
  d: path("M14 3a7 7 0 0 0-6.931 6.017A5.5 5.5 0 0 0 7.5 20h4.516a7.5 7.5 0 0 1 13.878-4.422Q26 15.055 26 14.5a5.5 5.5 0 0 0-5.069-5.483A7 7 0 0 0 14 3m12 16.5a6.5 6.5 0 1 1-13 0a6.5 6.5 0 0 1 13 0m-6-4a.5.5 0 0 0-1 0v6.793l-2.146-2.147a.5.5 0 0 0-.708.708l3 3a.5.5 0 0 0 .351.146h.006c.127 0 .254-.05.35-.146l3-3a.5.5 0 0 0-.707-.708L20 22.293z");
}

</style>
