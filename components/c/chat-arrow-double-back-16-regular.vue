<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="igq161bsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-arrow-double-back-16-regular" /></template>
<style>
.igq161bsd {
  fill: currentColor;
  d: path("M8 1a7 7 0 0 1 6.964 6.29a5.5 5.5 0 0 0-1.308-1.294A6.002 6.002 0 0 0 2 8c0 1.18.341 2.28.93 3.207a.5.5 0 0 1 .052.426l-.692 2.075l2.076-.691c.15-.033.29-.034.426.052c.374.238.778.432 1.202.583c.355.507.793.95 1.295 1.312a7 7 0 0 1-2.827-.925l-2.804.936a.5.5 0 0 1-.633-.633l.934-2.806A7 7 0 0 1 8 1m2.5 5a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M9.354 8.646a.5.5 0 0 0-.707 0l-1.5 1.5a.5.5 0 0 0 0 .707l1.5 1.5a.5.5 0 1 0 .707-.707L8.207 10.5l1.147-1.146a.5.5 0 0 0 0-.708m2.5 0a.5.5 0 0 0-.707 0l-1.5 1.5a.5.5 0 0 0 0 .707l1.5 1.5a.5.5 0 0 0 .707-.707L11.207 11H13v.5a.5.5 0 0 0 1 0V11a1 1 0 0 0-1-1h-1.793l.647-.646a.5.5 0 0 0 0-.708");
}

</style>
