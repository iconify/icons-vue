<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lxlqi7bce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:checkmark-starburst-32-filled" /></template>
<style>
.lxlqi7bce {
  fill: currentColor;
  d: path("M8.112 4.734a3.995 3.995 0 0 1 5.612-2.297l1.425.731c.567.29 1.237.293 1.806.008l1.433-.718a3.994 3.994 0 0 1 5.59 2.344l.493 1.524a2 2 0 0 0 1.271 1.282l1.52.505a3.995 3.995 0 0 1 2.297 5.612l-.73 1.425a2 2 0 0 0-.009 1.806l.718 1.433a3.994 3.994 0 0 1-2.344 5.59l-1.524.493a2 2 0 0 0-1.282 1.271l-.505 1.52a3.995 3.995 0 0 1-5.611 2.297l-1.426-.73a2 2 0 0 0-1.806-.009l-1.432.718a3.995 3.995 0 0 1-5.591-2.344l-.493-1.524a2 2 0 0 0-1.27-1.282l-1.52-.505a3.995 3.995 0 0 1-2.297-5.611l.73-1.426c.29-.567.293-1.237.008-1.806l-.718-1.432a3.995 3.995 0 0 1 2.344-5.591l1.524-.493a2 2 0 0 0 1.282-1.27zm14.594 6.559a1 1 0 0 0-1.414 0l-6.793 6.793l-3.293-3.293a1 1 0 0 0-1.414 1.414l4 4a1 1 0 0 0 1.414 0l7.5-7.5a1 1 0 0 0 0-1.414");
}

</style>
