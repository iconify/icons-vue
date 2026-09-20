<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gis69pbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-arrow-double-back-16-filled" /></template>
<style>
.gis69pbiw {
  fill: currentColor;
  d: path("M8 1a7 7 0 0 1 6.964 6.29a5.5 5.5 0 1 0-7.675 7.675a7 7 0 0 1-2.827-.926l-2.804.936a.5.5 0 0 1-.633-.633l.934-2.806A7 7 0 0 1 8 1m2.5 5a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M9.354 8.646a.5.5 0 0 0-.708 0l-1.5 1.5a.5.5 0 0 0 0 .707l1.5 1.5a.5.5 0 0 0 .708-.707L8.207 10.5l1.147-1.146a.5.5 0 0 0 0-.707m2.5 0a.5.5 0 0 0-.707 0l-1.5 1.5a.5.5 0 0 0 0 .707l1.5 1.5a.5.5 0 1 0 .707-.707L11.207 11H13v.5a.5.5 0 0 0 1 0V11a1 1 0 0 0-1-1h-1.793l.646-.646a.5.5 0 0 0 0-.707");
}

</style>
